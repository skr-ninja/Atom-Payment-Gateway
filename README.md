# Atom-Payment-Gateway


# Atom Payment Gateway Integration process

Add jar file in your project libs folder


1.MobilePaymentSDKOutput.jar

2. secure-data.jar

3. xercesImpl-2.6.2-jaxb-1.0.6.jar

and include asdk(Atom Sdk) dependency your project gradle file
After adding jar file.

After include jar file and dependency your project build gradle file showing.

    implementation project(path: ':asdk')
    implementation files('libs\\MobilePaymentSDKOutput.jar')
    implementation files('libs\\secure-data.jar')
    implementation files('libs\\xercesImpl-2.6.2-jaxb-1.0.6.jar')
    
    
   
