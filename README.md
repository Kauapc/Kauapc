'''java
package aula;

public class Exemplo {
	private String professor;
	private String disciplina;
	private int qnt_aulas;
	public String getProfessor() {
		return professor;
	}
	public void setProfessor(String professor) {
		this.professor = professor;
	}
	public String getDisciplina() {
		return disciplina;
	}
	public void setDisciplina(String disciplina) {
		this.disciplina = disciplina;
	}
	public int getQnt_aulas() {
		return qnt_aulas;
	}
	public void setQnt_aulas(int qnt_aulas) {
		this.qnt_aulas = qnt_aulas;
	}
	public void BoasVindas(String a) {
		System.out.println("Boas Vindas " + a);
	}
	
}


package aula;

public class Ex {

	public static void main(String[] args) {
		Exemplo puxa = new Exemplo();
		
		puxa.setDisciplina("Programação 2");
		puxa.setProfessor("clecio");
		puxa.setQnt_aulas(4);
		puxa.BoasVindas(puxa.getProfessor());
		
		System.out.println(puxa.getDisciplina());
		System.out.println(puxa.getProfessor());
		System.out.println(puxa.getQnt_aulas());
		
		
	}

}

'''java
