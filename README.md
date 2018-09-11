# Text-exception

public class TestException {

	public static void main(String[]args){
		
		ExceptionA firstexception = new ExceptionA("Perdio Peru");
		ExceptionB secondexception = new ExceptionB("Perdio Argentina");
		ExceptionC thirdexception = new ExceptionC("Perdio Colombia");
		
		try{
			throw firstexception;
		}catch(ExceptionA excepta){
			excepta.printStackTrace();
		}
		
		try {
			throw secondexception;
		}catch(ExceptionA excepta){
			excepta.printStackTrace();
		}
		
		try{
			throw thirdexception;
		}catch(ExceptionA excepta){
			excepta.printStackTrace();
		}
	}

	
}
