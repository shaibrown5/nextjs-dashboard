# Next.js Dashboard Application

A modern, full-stack dashboard application built with Next.js 15, featuring comprehensive invoice management, customer tracking, and real-time analytics.

## 🚀 Features

### **Dashboard Overview**
- **Revenue Analytics**: Interactive charts showing monthly revenue trends
- **Key Metrics Cards**: Real-time display of total customers, invoices, paid amounts, and pending amounts
- **Latest Invoices**: Recent invoice activity with customer details
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### **Invoice Management**
- **Invoice Listing**: Paginated table with search functionality
- **Create Invoices**: Form-based invoice creation with customer selection
- **Edit Invoices**: Update existing invoice details and status
- **Invoice Status**: Track paid, pending, and overdue invoices
- **Search & Filter**: Find invoices by customer name, email, or amount

### **Customer Management**
- **Customer Directory**: View and manage customer information
- **Customer Profiles**: Individual customer pages with contact details
- **Customer Images**: Avatar support for customer profiles

### **Authentication & Security**
- **Login System**: Secure authentication with NextAuth.js
- **Protected Routes**: Dashboard access requires authentication
- **Form Validation**: Client and server-side validation
- **Error Handling**: Comprehensive error boundaries and user feedback

### **Technical Features**
- **Server Actions**: Modern form handling with React Server Actions
- **Database Integration**: PostgreSQL database with optimized queries
- **Real-time Data**: Live updates with Suspense boundaries
- **TypeScript**: Full type safety throughout the application
- **Tailwind CSS**: Modern, responsive styling
- **Performance**: Optimized loading states and skeleton components

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Database**: PostgreSQL with postgres.js
- **Authentication**: NextAuth.js 5
- **Styling**: Tailwind CSS with custom components
- **Icons**: Heroicons
- **Forms**: React Server Actions with Zod validation
- **Deployment**: Vercel-ready configuration

## 📁 Project Structure

```
app/
├── dashboard/           # Main dashboard pages
│   ├── (overview)/     # Dashboard overview with analytics
│   ├── customers/      # Customer management
│   └── invoices/       # Invoice management (list, create, edit)
├── login/              # Authentication pages
├── ui/                 # Reusable UI components
└── lib/                # Database utilities and data fetching
```

## 🚀 Getting Started

1. **Install dependencies**:
   ```bash
   pnpm install
   ```

2. **Set up your database**:
   - Configure PostgreSQL connection
   - Set `POSTGRES_URL` environment variable

3. **Run the development server**:
   ```bash
   pnpm dev
   ```

4. **Open your browser**:
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📚 Learning Resources

This project is part of the [Next.js App Router Course](https://nextjs.org/learn) and demonstrates modern React patterns including:

- Server Components and Client Components
- Server Actions for form handling
- Database integration with PostgreSQL
- Authentication with NextAuth.js
- Responsive design with Tailwind CSS
- TypeScript for type safety
- Error boundaries and loading states

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
