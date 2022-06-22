//
//
//
//
import  { Cliente }  de  "./cliente" ;
import  { ItemNotaFiscal }  de  "./item_nota_fiscal" ;
export  class  NotaFiscal  {

    /* Atributos */
    id : número ;
    código : número ; 
    dados : Data ;
    cliente : Cliente ;
    itens :   Array < ItemNotaFiscal > ;  
    valorNota : número ;

    /* Métodos */

    /* Construtor de métodos */    
    construtor  ( id : número ,  codigo : número ,  cliente : Cliente  )  {
        isso . id  =  id ;
        isso . codigo  =  codigo ;
        isso . data  =  new  Data ( ) ; 
        isso . cliente  =  cliente ; 
        isso . valorNota  = 0,0 ;
        isso . items  =  new  Array < ItemNotaFiscal > ( ) ;


    }

    /* Métodos Acessores */
    getid ( ) : numero  {
        devolva  isso . identificação ;
    }

    getcodigo ( ) : numero  {
        devolva  isso . código ;
    }

    getdata ( ) : Data  {
        devolva  isso . dados ;
    }

    /* Métodos Modificadores */     
    setcodigo ( codigo : número ) : void  {
        isso . codigo  =  codigo ;
    }

    setdata ( data : Data ) : void  {
        isso . dados  =  dados ;
    }

     

    adicionarItem ( item : ItemNotaFiscal )  {
        isso . itens . empurrar ( item ) ;
        
        isso . valorNota  +=  item . valor ;
    }

    // Percorrer os itens do array e calcular o valor total da NotaFiscal
    calcularValorNotaFiscal ( ) : número  {
        deixe  valorCalculado  =  0 ;


        return  valorCalculado ;

    }

    // Imprime uma NotaFiscal conforme o Layout definido
    
    imprimirNotaFiscal ( ) : void  {


    }

    
}
