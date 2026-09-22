## 👩‍💻 My Role — Backend Development

I worked on the **backend development and data integration** of Journey, focusing on connecting the application's data layer with the frontend and supporting dynamic railway ETA updates.

### 🔧 Backend Responsibilities

- 🗄️ Designed and managed the **Supabase/PostgreSQL database**
- 📊 Created and structured database tables for railway and train information
- 🔑 Worked with **Primary Keys and database relationships**
- 🔄 Implemented data insertion and update operations using **Upsert**
- 🔐 Configured **Row Level Security (RLS)** for database access
- ⚡ Created database **indexes** to improve query performance
- 🕒 Implemented `updated_at` handling for tracking record updates
- 🔌 Integrated the database with the application through **REST APIs**
- 🔄 Supported **polling-based data updates** for dynamically updated train information
- 🔗 Connected backend data with the application's ETA prediction workflow
- 🧪 Tested database operations and API integration
- 🚀 Assisted with backend integration during application deployment

### 🛠️ Technologies Used

- **Supabase**
- **PostgreSQL**
- **REST API**
- **Next.js API Integration**
- **SQL**
- **Git & GitHub**

### 🔄 Backend Data Flow

```text
Railway / Train Data
        ↓
Supabase PostgreSQL
        ↓
Database Operations
        ↓
REST API
        ↓
ETA / Train Information
        ↓
Next.js Frontend
