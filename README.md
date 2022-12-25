# Mantine-styled Formik Components in Typescript

**Notice: This repository is no longer maintained, beacuse the author has switched to using react-hook-from and zod. [Here](https://github.com/Rayologist/rhf-zod-mantine-typescript-template) is the repository that is being actively mantained**

This [mantine-next-template](https://github.com/mantinedev/mantine-next-template) integrates [Formik](https://github.com/jaredpalmer/formik) as a means of form contol and [Yup](https://github.com/jquense/yup) as form validtion. Input components developed by Mantine can be easily controlled through `<FormikController />`.

## The `useSimpleForm` Hook

A custom hook `useSimpleForm` is implemented to solve the problem of boilerplate codes when developers are constructing Formik forms, as shown in `src/pages/index.tsx`. The simple form example is adapted from [Mantine UI](https://ui.mantine.dev/category/authentication#authentication-title), and can be found in `src/pages/simple-form.tsx`.

![Sample Form](assets/form.png)

## Getting Started

First, run the development server:

```bash
pnpm dev
# or
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Contact

If you have any questions, please feel free to contact me at rayologist1002@gmail.com
