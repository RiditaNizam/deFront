public String deFront(String str) {    
  
  String answerString = "";
  
  if(str.charAt(0) == 'a' && str.charAt(1) == 'b'){
    answerString += str;
  }

  else if(str.charAt(0) == 'a'){
    answerString += str.charAt(0) + str.substring(2);
  }
  
  else if(str.charAt(1) == 'b'){
    answerString += str.substring(1);
  }
  
  else{
    answerString += str.substring(2);
  }
  
  return answerString;
  
}
