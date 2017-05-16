# Case-Switch
Using Case Switch with Telephone Numbers

public class TelephoneNumbers {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int numberEntered= 9;
		
		
		String value;
		switch (numberEntered){
		
		case 1: value ="Nothing defined for 1";
		break;
		
		case 2: value = "A,B,C";
		break;
		
		case 3: value = "D,E,F";
		break;
		
		case 4: value = "G,H,I";
		break;
		
		case 5: value = "J,K,L";
		break;
		
		case 6: value = "M,N,O";
		break;
		
		case 7: value = "P,Q,R,S";
		break;
		
		case 8: value = "T,U,V";
		break;
		
		case 9: value = "W,X,Y,Z";
		break;
				
		default: value = "Not defined";
		break;
		}
		
		System.out.println(value);
		
		
		}

	}
