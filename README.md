# About

This is the repository that follows along with my [create-t3-app](https://brandon-lent.com/tags/create-t3-app-gov) investigation. I've sectioned off relevant changes into their own commits so you can view individual, relevant changes.

## Setup

To get setup with this repository, you can follow along below:

### Clone repository to folder of your choice
```
git clone https://github.com/brandon-lent/Mock-benefits-app.git
```

### Install dependencies
```
cd Mock-benefits-app
npm install
```

### Set environment variables
tk

### Start application
```
npm run dev
```


## Technical Context

### [Create T3 App](https://create.t3.gg/)

This application has been built using the create-t3-app stack. The options I've chosen for setup follows:

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [tRPC](https://trpc.io)


### [USWDS](https://designsystem.digital.gov/)
I've chosen to use the United States Web Design system for all styling. The reason being:
- It's a common design system choice among government clients
- It's fairly easy to get setup and working

### [Storybook](https://storybook.js.org/)
Storybook is a way to render individual pages / components in an easily shareable format. This is overall a great tool when collaborated with non-engineers and also makes local development and testing easier.





