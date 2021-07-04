#Prática Decorators em Python
#Nomes: Andriza e Iuri

authenticated = 1
#authenticated = 0

status = "Estudando Python =D"

def checkAuth(func):
  def check():
    
    if(authenticated == 1):
      func()
    else:
      print("Not Authenticated!")

  return check


@checkAuth
def postStatus():
  print(status)

#postStatus = checkAuth(postStatus)

postStatus()
