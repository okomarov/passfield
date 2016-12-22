![password field](https://raw.githubusercontent.com/okomarov/passfield/master/Example.PNG)

##### Syntax
    passdlg(uitype) It will always produce one masked password field plus the  
           optional components:
             * 'u' or 'UsernameField'
             * 'c' or 'ConfirmPass'
             * 's' or 'ShowHideCheckBox'

           UITYPE can be a cell array with above named fields or a string with
           the initial letters 'u', 'c' and 's', e.g. passdlg('cs').

    passdlg(..., Name, Value) For valid Name/Value pairs refer to Figure Properties

    passfield(Name, Value) For valid Name/Value pairs refer to the Uicontrol Properties
           plus the following:
             * 'EchoChar'  -   character displayed in field
             * 'Password'  -   plain text string of the password

##### Warning: 

  This code heavily relies on undocumented and unsupported Matlab functionality.
  Use at your own risk!


##### Examples:

    passdlg();
    passdlg('us');
    passdlg usc

 
See also: [Uicontrol Properties](http://www.mathworks.co.uk/help/matlab/ref/uicontrol_props.html), [uicontrol](http://www.mathworks.co.uk/help/matlab/ref/uicontrol.html), javacomponent



#### Additional resources
- The [Undocumented Matlab](http://undocumentedmatlab.com/) blog by Yair Altman. A gold mine of Matlab's undocumented features. 
