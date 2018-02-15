public class Vetores {
   
    private int [] vetor;
    int tamanho = 0;
    
    public int criaVetor(int tamanho){
         vetor = new int [tamanho];
         return tamanho;
    }

    public void buscaItem(){
        
    }
    
    public void removeItem(){
        tamanho = tamanho - 1;
    }
    
    public int verificaMaior(){
        int maior = vetor [0];
          for(int i = 0; i< vetor.length; i++){
              if(maior < vetor[i]){
                  maior = vetor [i];
              }
          }
          
        return maior;
    }
    
    public int verificaMenor(){
        int menor = vetor [0];
          for(int i = 0; i< vetor.length; i++){
              if(menor < vetor[i]){
                  menor = vetor [i];
              }
          }
              return menor;
    }   
    
    public static void main(String[] args) {
        Scanner leitor = new Scanner (System.in);
        
        //inserir manualmente o valor no vetor
        int [] vetor = new int [3];
        
        //mostrar o tamanho do vetor
        System.out.println(vetor.length);
        
        //buscar valor desejado no vetor
                
        //remover valores do vetor, se houver valores
        
        //inserir novo valor no final do vetor, se houver espaço
        
    

}
