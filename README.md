# atvAbella1TEST
Apenas o que consegui fazer

> CÓDIGO ABAIXO:


package exer.p3.abella;

public class Conta {
	    public int agencia;
	    public int conta;
	    private String titular; 
	    private double saldo;
	    private double limite;
	    private double valorLimite;
	    
	    public Conta() {
	    	this.agencia =0;
	    	this.conta =0;
	    	this.titular = " ";
	    	this.saldo = 0;
	    	this.limite = 0;
	    }
	    
	    
		public int getAgencia() {
			return agencia;
		}
		public void setAgencia(int agencia) {
			this.agencia = agencia;
		}
		public int getConta() {
			return conta;
		}
		public void setConta(int conta) {
			this.conta = conta;
		}
		public String getTitular() {
			return titular;
		}
		public void setTitular(String titular) {
			this.titular = titular;
		}
		public double getSaldo() {
			return saldo;
		}
		public void setSaldo(double saldo) {
			this.saldo = saldo;
		}
		public double getLimite() {
			return limite;
		}
		public void setLimite(double limite) {
			this.limite = limite;
		}
		public double getValorLimite() {
			return valorLimite;
		}
		public void setValorLimite(double valorLimite) {
			this.valorLimite = valorLimite;
		}
	    
		public void depositarValor (double valor) {
			this.saldo = this.saldo + valor;
			
		}
		

	
		public void inserirDados(int a, int b, String c, float d, float z) {
		
		this.agencia = a;
    	this.conta = b;
    	this.titular = c;
    	this.saldo = d;
    	this.limite = z;
		
	   }
		
	     public void sacar(double valor) {
	        this.saldo = this.saldo - valor;
	        }
	     
	     // boolean sacar(double valor){
	    //    if(valor>0)
	    //        this.saldo-=valor;
	    //        return true;
	   //    else
	   //         return false;
	    // Pensei em fazer assim, porém não sabia se estaria correto
	     //pois pediu public void (o mesmo vale pra os demais, mas so anotei aqui)
	   
	     
}





package TreeSet2;
import java.util.ArrayList;
import java.util.Collection;
import java.util.Collections;
import java.util.Iterator;
import java.util.TreeSet;
public class TreeSetDEC {
	 
	   public static void main(String[] args) {
		   
	      ArrayList <Integer> listaInteiros= new ArrayList<>();
	      
	      for (int i=1;i<1001;i++){
		       listaInteiros.add(i); 
		      
	    	  
	      }
	      
	      Collections.sort(listaInteiros);
	      
	      
	      for (Integer elemento: listaInteiros) {
	    	  System.out.println(elemento);
	      }
	      
	      
	      Collections.sort(listaInteiros, Collections.reverseOrder());
	      
	      
	      for (Integer elemento : listaInteiros) {
	    	  System.out.println(elemento);
	      }
	}
	   
}

