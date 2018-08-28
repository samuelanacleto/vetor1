package aula20;

public class vetor1 {

	public static void main(String[] args) {
		int v[] = new int [5];
		v[0]=1;
		v[1]=2;
		v[2]=3;
		v[3]=4;
		v[4]=5;
		
		for(int i=0;i<v.length;i++){
			System.out.println(v[1]);
		}
		
	}

}
////////////////////////////////////////////////////////
pegando maior e menor valor em um vetor


package aula20;

public class vetor1 {

	public static void main(String[] args) {
		int v[] = new int [10];
		int maior,menor;
		v[0]=10;
		v[1]=-1;
		v[2]=20;
		v[3]=130;
		v[4]=56;
		v[5]=-6;
		v[6]=896;
		v[7]=80;
		v[8]=90;
		v[9]=100;
		maior=v[0];
		menor=v[0];
		
		for(int i=0;i<v.length;i++){
						
		if(v[i]>maior)
			maior=v[i];
		else
		if (v[i]<menor)
			menor=v[i];
			}
		
		System.out.println ("maior numero: " +maior);
		System.out.println ("menor numero: " +menor);
	}
}
