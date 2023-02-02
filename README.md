[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9977581&assignment_repo_type=AssignmentRepo)
# Cheeky Smiles


Cheeky Smiles owns a party hosting company. He would like a more efficient way to charge customers for parties. Cheeky Smiles has decided to write a python algorithm that can automatically email invoices to customers. The invoices should include the line-item prices for the customer's request. 

The party price starts at **$100** for the basic package. The customers can pay extra for any addons.  

**Addons Price List:**
- Bouncy House (H): $50
- Slip & Slide (S): $40
- Yard Sign (Y): $35
- Pizza (p): $10 per pizza
- Burger (b): $2 per burger
- Soda (s): $.50 per soda
- Cake (C): $15
- Cupcakes (c): $.25 per cupcake


Example Input:

```
"1H,20c,20b,4p,20s"
```

Example Output:
```
Thank you for choosing Cheeky Smiles for your party needs! Here is your itemized invoice:

Bouncy House, 1, $50.00
Cupcakes, 20, $5.00
Burgers, 20, $40.00
Pizza, 4, $40.00
Soda, 20, $10.00

Base Price: 100
Total: $245.00
```
