# Portfolio Project Data — Pustakanesia - Digital Library

- **Category:** `web-development` (`Web Development`)
- **Accent Color:** `cyan`
- **Target Assets Folder:** `public/images/projects/pustakanesia_digital_library/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image16.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "pustakanesia-digital-library",
  "code": "PRO-13 // WEB-03",
  "title": "Pustakanesia - Digital Library",
  "category": "web-development",
  "categoryLabel": "Website",
  "year": "2023",
  "status": "Completed",
  "accentColor": "cyan",
  "repoUrl": "https://github.com/weztcy/Pustakanesia-Digital-Library",
  "license": "MIT License",
  "banner": "/images/projects/pustakanesia_digital_library/banner.webp",
  "summary": "Full-stack Laravel digital library platform managing book catalogs, student memberships, transactional circulation, and PDF reporting.",
  "projectDescription": "Pustakanesia is a full-stack Laravel digital library system built with PHP, MySQL, Blade, and Tailwind CSS. It streamlines catalog indexing, student membership profiles, atomic book borrowing and return workflows with a three-book active quota, and DomPDF circulation report exports.",
  "architectureSummary": "Blade + Tailwind CSS frontend routed through Laravel auth middleware to MVC controllers, Eloquent ORM, DomPDF, and a relational MySQL database.",
  "techStack": [
    "PHP",
    "Laravel",
    "MySQL",
    "Blade",
    "Tailwind CSS",
    "Bootstrap",
    "Sass",
    "JavaScript",
    "jQuery",
    "Select2",
    "SweetAlert2",
    "DomPDF",
    "Laravel Mix",
    "Composer",
    "npm"
  ],
  "telemetryMatrix": {
    "projectType": "Full-Stack Web Application",
    "targetPlatform": "Web Browser",
    "primaryDomain": "Digital Library Management",
    "architecturePipeline": "Laravel MVC + Eloquent + MySQL",
    "testingAndAudit": "Passed",
    "projectStatus": "Completed",
    "projectYear": "2023"
  },
  "projectInfo": {
    "projectType": "Full-Stack Digital Library System",
    "developmentStatus": "Completed",
    "developmentYear": "2023",
    "platform": "Web Browser",
    "projectCategory": "Web Development"
  },
  "projectBackground": "Campus and institutional libraries relying on manual ledgers struggle to track real-time book availability, enforce borrowing limits, and compile circulation audits. Pustakanesia digitizes catalog discovery, member registration, and loan lifecycle management into a unified web portal for librarians and student borrowers.",
  "problemStatements": [
    {
      "title": "Fragmented Book Availability Tracking",
      "description": "Manual borrowing logs make it difficult for staff and students to verify in real time whether a specific catalog title is in stock or currently checked out.",
      "issueCode": "ISSUE_01"
    },
    {
      "title": "Unenforced Member Borrowing Quotas",
      "description": "Without centralized loan counting per student account, borrowers can exceed the maximum active circulation limit of three simultaneous books.",
      "issueCode": "ISSUE_02"
    },
    {
      "title": "Disconnected Member & Academic Records",
      "description": "Authentication credentials and academic metadata such as student IDs (NPM), study programs, and contact details are difficult to reconcile when stored outside a relational schema.",
      "issueCode": "ISSUE_03"
    },
    {
      "title": "Manual Circulation Audit Reporting",
      "description": "Preparing periodic borrowing and return recaps by hand is time-consuming and prone to transcription errors compared to automated database-driven PDF exports.",
      "issueCode": "ISSUE_04"
    }
  ],
  "projectObjectives": [
    {
      "title": "Centralized Searchable Book Catalog",
      "description": "Deliver a paginated book directory with unique catalog codes, cover imagery, many-to-many category tagging, and live status indicators.",
      "targetTag": "TARGET_01"
    },
    {
      "title": "Atomic Circulation & Quota Enforcement",
      "description": "Guarantee consistent loan creation and book status updates using database transactions while capping active unreturned loans at three books per member.",
      "targetTag": "TARGET_02"
    },
    {
      "title": "Role-Separated Admin & Member Workspaces",
      "description": "Serve tailored dashboards and navigation menus for administrators and student members backed by Laravel session authentication and the isAdmin flag.",
      "targetTag": "TARGET_03"
    },
    {
      "title": "One-Click PDF Circulation Reports",
      "description": "Generate formatted borrowing recapitulation reports directly from Eloquent loan queries using DomPDF.",
      "targetTag": "TARGET_04"
    }
  ],
  "coreFeatures": [
    {
      "title": "Role-Based Dashboards & Navigation",
      "description": "Routes authenticated administrators to KPI metrics and full circulation logs while routing student members to personal loan summaries and borrowing regulations.",
      "badge": "Access Control"
    },
    {
      "title": "Catalog & Multi-Category Management",
      "description": "Supports full CRUD operations on books and categories, cover image uploads, pagination, search filtering, and Select2 multi-category assignment.",
      "badge": "Catalog"
    },
    {
      "title": "Transactional Borrowing & Return Flow",
      "description": "Automatically assigns a seven-day return deadline, enforces the three-book active limit, and synchronizes buku.status between In Stock and dipinjam inside DB transactions.",
      "badge": "Circulation"
    },
    {
      "title": "Student Member & Profile Administration",
      "description": "Manages student profiles with unique NPM validation, study program metadata, residential address, phone contact, and custom avatar uploads.",
      "badge": "Membership"
    },
    {
      "title": "Automated DomPDF Reporting",
      "description": "Compiles complete riwayat_pinjam histories with borrower and book relations into a styled downloadable laporan_peminjaman.pdf file.",
      "badge": "Reporting"
    }
  ],
  "interfaceShowcase": [
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image01.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image02.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image03.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image04.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image05.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image06.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image07.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image08.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image09.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image10.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image11.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image12.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image13.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image14.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image15.webp"
    },
    {
      "imageUrl": "/images/projects/pustakanesia_digital_library/image16.webp"
    }
  ],
  "userFlow": {
    "summary": "Authenticated members or administrators sign in, browse or manage the catalog, and execute borrowing or return transactions. Each loan validates the three-book active limit, sets a seven-day return date, updates book stock atomically, and feeds live dashboards and PDF audit exports.",
    "steps": [
      {
        "step": "01",
        "title": "Authentication & Role Dispatch",
        "description": "Users log in or register with student profile details; HomeController inspects isAdmin to render either the Administrator Dashboard or Member Reading Room.",
        "actorOrNode": "HomeController / Auth"
      },
      {
        "step": "02",
        "title": "Catalog Discovery & Filtering",
        "description": "Users browse paginated book cards, search by title, or filter collections by category via BukuController and KategoriController.",
        "actorOrNode": "BukuController / Blade UI"
      },
      {
        "step": "03",
        "title": "Loan Eligibility & Quota Check",
        "description": "When submitting a loan request, RiwayatPinjamController queries unreturned loans for the borrower and blocks submission if three active loans exist.",
        "actorOrNode": "RiwayatPinjamController"
      },
      {
        "step": "04",
        "title": "Transactional Borrowing Execution",
        "description": "Inside DB::beginTransaction(), the system inserts a riwayat_pinjam row with a seven-day due date and updates buku.status to dipinjam.",
        "actorOrNode": "MySQL Transaction"
      },
      {
        "step": "05",
        "title": "Book Return & Stock Restoration",
        "description": "Administrators process returns via PengembalianController, stamping tanggal_pengembalian and restoring buku.status to In Stock atomically.",
        "actorOrNode": "PengembalianController"
      },
      {
        "step": "06",
        "title": "Circulation Audit & PDF Export",
        "description": "Staff review the searchable loan ledger or invoke CetakLaporanController to download a formatted PDF recap of all transactions.",
        "actorOrNode": "CetakLaporanController / DomPDF"
      }
    ]
  },
  "systemArchitecture": {
    "summary": "Pustakanesia implements a layered Laravel MVC monolith backed by MySQL. Blade views styled with Tailwind CSS communicate over session-authenticated web routes to resource controllers, which coordinate Eloquent models, atomic transactions, local media storage, and DomPDF rendering.",
    "layers": [
      {
        "name": "Client Presentation Layer",
        "role": "Renders responsive role-aware dashboards, searchable tables, multi-select inputs, and feedback alerts.",
        "components": ["Blade Templates", "Tailwind CSS", "Select2", "SweetAlert2"]
      },
      {
        "name": "Routing & Middleware Layer",
        "role": "Enforces session authentication, CSRF protection, and HTTP verb mapping across web endpoints.",
        "components": ["routes/web.php", "Authenticate Middleware", "VerifyCsrfToken"]
      },
      {
        "name": "Application Controller Layer",
        "role": "Handles request validation, role branching, transactional borrowing/return logic, and PDF streaming.",
        "components": ["HomeController", "BukuController", "KategoriController", "AnggotaController", "RiwayatPinjamController", "PengembalianController", "CetakLaporanController", "ProfileController"]
      },
      {
        "name": "Persistence & Storage Layer",
        "role": "Manages relational tables, foreign-key cascades, Eloquent relationships, and uploaded cover/avatar assets.",
        "components": ["MySQL", "Eloquent ORM", "Laravel Migrations & Seeders", "DomPDF", "Local Public Storage"]
      }
    ]
  },
  "databaseDataFlow": {
    "type": "Database Schema / ERD",
    "summary": "Relational MySQL schema linking authentication users with one-to-one student profiles, many-to-many book-category assignments, and transactional borrowing history records.",
    "entitiesOrPipelines": [
      {
        "name": "users",
        "type": "Table",
        "fields": ["id", "name", "email", "password", "isAdmin", "created_at", "updated_at"]
      },
      {
        "name": "profile",
        "type": "Table",
        "fields": ["id", "npm", "prodi", "alamat", "noTelp", "photoProfile", "users_id", "created_at", "updated_at"]
      },
      {
        "name": "buku",
        "type": "Table",
        "fields": ["id", "kode_buku", "judul", "pengarang", "penerbit", "tahun_terbit", "deskripsi", "gambar", "status", "created_at", "updated_at"]
      },
      {
        "name": "kategori",
        "type": "Table",
        "fields": ["id", "nama", "deskripsi", "created_at", "updated_at"]
      },
      {
        "name": "kategori_buku",
        "type": "Table",
        "fields": ["id", "buku_id", "kategori_id", "created_at", "updated_at"]
      },
      {
        "name": "riwayat_pinjam",
        "type": "Table",
        "fields": ["id", "users_id", "buku_id", "tanggal_pinjam", "tanggal_wajib_kembali", "tanggal_pengembalian", "created_at", "updated_at"]
      }
    ]
  },
  "technicalImplementation": [
    {
      "category": "Transactional Consistency",
      "title": "Atomic Loan & Return Synchronization",
      "description": "RiwayatPinjamController::store() and PengembalianController::pengembalian() wrap loan record inserts/updates and buku.status mutations inside DB::beginTransaction() and DB::commit() with rollback handling to prevent desynchronized inventory states.",
      "badge": "ACID Transactions"
    },
    {
      "category": "Business Rules",
      "title": "Three-Book Active Quota & 7-Day Loan Term",
      "description": "Before persisting a borrowing record, RiwayatPinjamController counts open transactions where tanggal_pengembalian is null, rejecting requests at three or more active loans and computing tanggal_wajib_kembali seven days ahead via Carbon.",
      "badge": "Quota Guard"
    },
    {
      "category": "Validation & Storage",
      "title": "Unique NPM Enforcement & Safe Asset Replacement",
      "description": "ProfileController and AnggotaController enforce unique npm validation using Rule::unique('profile', 'npm')->ignore() and automatically delete superseded custom profile photos while preserving the default boy.png avatar.",
      "badge": "Data Integrity"
    },
    {
      "category": "Document Export",
      "title": "Eloquent-Backed DomPDF Report Generation",
      "description": "CetakLaporanController eager-loads user and buku relationships on Peminjaman records and renders peminjaman.laporan_pdf into a downloadable laporan_peminjaman.pdf file.",
      "badge": "PDF Engine"
    }
  ],
  "primaryTechSpecs": {
    "programmingLanguage": "PHP",
    "framework": "Laravel",
    "database": "MySQL"
  },
  "architectureQuality": {
    "badges": [
      "Transactional Integrity",
      "Role Based Access",
      "Relational Schema",
      "PDF Reporting"
    ]
  }
}
```
