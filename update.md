UPDATE: 
Please note that some policies may not be added to the json list in the polygon_policy.sh file. 
SecondaryAccountUseEnabled was just added to the list. 
By default, if you use a Policy Editor and the creator forgets to add a policy such as the mentioned policy above, the policy will be set to what it's set to by default by your School Admin. 
Meaning if SecondaryAccountUseEnabled is set to false by default, and that Policy isn't added to the Policy Editor it will stay as false, and if you try to use Nano, VIM, or sudo sed to enable it or set it to true and or false, it will enable or disable the policy, but it will create a conflicting value which is hard to look at.
(It won't really cause any harm) it's just annoying as hell to look at.

If you notice a specific Policy that is not added to the json list on the polygon_policy.sh file please let me know and i will add it to the list. Please also specify if it's a command that should be set to true / enabled or false / disabled.
