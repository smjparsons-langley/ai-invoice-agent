ai-invoice-agent/
├── src/
│   ├── agents/
│   │   └── invoiceAgent.ts
│   ├── api/
│   │   ├── cron.ts          # Vercel cron endpoint
│   │   └── auth.ts          # OAuth callback
│   ├── services/
│   │   ├── gmailService.ts
│   │   ├── openaiService.ts
│   │   ├── pdfService.ts
│   │   └── db.ts            # Mock DB (replace with Supabase/Postgres)
│   ├── templates/
│   │   └── invoice.html
│   └── types.ts
├── public/
│   └── logo.png
├── package.json
├── tsconfig.json
├── vercel.json
└── README.md
