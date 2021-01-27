# AtividadesLG2
Atividades da disciplina Lógica 2 - Professor Johnata
Aluna Giulia Santana dos Anjos


Código Pilha 

import java.util.LinkedList;
import java.util.List;

Public class Pilha {

	private List<String> nomes = newLinkedList<String>();

	public void push(String nome) {
		nomes.add(nome);
	}

	public String pop() {
		Return nomes.remove(nomes.size()-1);
	}

	public boolean vazia() {
	return nomes.size() == 0;
	}
}


Código Fila 

import java.util.LinkedList;
import java.util.List;

Public class Fila {

	private List<String>  alunos = new LinkedList<String.();

	public void adiciona(String aluno){
		alunos.add(aluno);
	}

	public String remove() {
		return alunos.remove(0);
	}

	public boolean vazia() {
		return alunos.isEmpty();
	}

	public String toString() {
		return alunos.toString();
	}
}
