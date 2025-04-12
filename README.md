# Digital Payment Wallet(MERN Stack)

A functional payment application with core wallet features, built as a full-stack project using MongoDB, Express, React, and Node.js.

## Current Implementation

### What's Working
 **User Authentication**  
- JWT-based signup/login/logout
- Basic session management

**Payment Features**  
- Wallet balance system
- Send/receive money between users
- Multiple payment sources:
  - Wallet balance
  - Linked bank accounts 

 **Utilities**  
- QR code generation/scanning 
- Basic transaction history
- Notification system for payments

 **Bill Payments**  
- UI templates for:
  - Electricity
  - Gas
  - Water
  - Mobile recharge


### Technical Stack
- **Frontend**: React with basic state management
- **Backend**: Node/Express REST API
- **Database**: MongoDB (local/Atlas)
- **Auth**: JWT tokens
- **Testing**: Manual testing completed


## Getting Started
1. Clone repo
2. `npm install` in both /client and /server
3. for starting use npm start
4. Set up MongoDB connection
5. `npm run dev` for development

## Next Steps
- [ ] Add proper payment gateway integration
- [ ] Implement two-factor authentication
- [ ] Build admin dashboard
- [ ] Write unit tests
