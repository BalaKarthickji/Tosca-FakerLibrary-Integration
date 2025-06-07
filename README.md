# Tosca-FakerLibrary-Integration

To try the synthetic test data generation, you can start with copying the files Faker.Net.4.8.dll, FakerData.dll, FakerData.pdb and add them to %Tbox% folder of Tosca installation(usually C:\Program Files (x86)\TRICENTIS\Tosca Testsuite\TBox)
Then import the module FakerDataGeneratorModules.tsu


Then you can use these modules just like TBox set buffer module.
Just give the buffername where you want to store the data. 
For example, if you want to get a Country to be stored in a buffer named coun, then
Use the module Faker Address Generator, then give the value as coun for the attribute Country with action mode as 'Buffer'. 


When running this test step, we will get a random country stored in a buffer named coun
If you have any queries, feel free to reach out to me via https://www.linkedin.com/in/contactbalaji/
