# AlertControl

AlertControl is a utility created to easily enable or disable alerting by service or customer.  

Components:
1. SharePoint List containing the name of each service, on/off column, along with a logo
2. As part of our Master Client List, a column for each service.  This enables turning individual alerts on/off for each customer
3. PowerApp to actually control all this
4. Daily email notification displaying all services/customers that are disabled


![image](https://user-images.githubusercontent.com/49880736/122790046-ecc8d480-d285-11eb-8984-18382e79da9c.png)
![image](https://user-images.githubusercontent.com/49880736/122790277-27cb0800-d286-11eb-9fce-e6b79dcbd5b4.png)
![image](https://user-images.githubusercontent.com/49880736/122790509-606ae180-d286-11eb-9275-f0a8216dd8f4.png)


Here's the flow that's called to determine the state.  It takes two parameters, the Service name and the Customer name.  It will return a single boolean value.

![AlertControlStateCheck](https://user-images.githubusercontent.com/49880736/122803926-41278080-d295-11eb-80b3-b1d53e8711f4.png)



