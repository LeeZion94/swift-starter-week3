Week3 [Step1] BaDook2.     
                    
이번 미션에서는 타입을 정의하고 인스턴스를 생성하기만 하면 되는 것 같아서 한 번 해봤습니다.                
                
구조체와 클래스의 차이는 (매우 많겠지만) 대표적으로 이니셜라이저가 있고 없고의 차이로 알고있기 때문에    
구조체 타입으로 만들어 봤습니다.     
      
-------business_design파일--------             
Person 구조체에서는     
사람마다 가지고 있는 돈이 다르다고 생각하여 변수 프로퍼티로 선언하였고      
buyCoffe()는 메서드로 선언만 하였습니다.        
      
Coffeeshop 구조체에서는    
매출액이 매일 달라지기 때문에 변수 프로퍼티로 선언하였고.    
바리스타는 바뀔 수 있기에 변수 프로퍼티로 선언하였고.     
메뉴는 자주 바뀌면 사장이 힘들어하기 때문에 let 딕셔너리로 선언하였습니다.          
pickUpTable(), takeOrder(),makeCoffee()도 마찬가지로 메서드로 선언만 하였습니다           
            
Coffee를 열거형으로 생성하였으나 이번 미션은 인스턴스를 생성해보는 경험을 하는 것이 목적인 것 같습니다.      
그래서 각 case의 rawValue 값은 String형으로 임의로 지정하였습니다.       
        
---------main파일--------------             
misterLee와 misKim의 소지한 돈은 바뀌지 않는다는 가정하에 let으로 선언하였고     
yagombucks는 CoffeShop을 하지 않으면 장사를 접는다는 가정하에 let으로 선언하였습니다.
