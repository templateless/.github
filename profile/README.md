[Templateless](https://templateless.com/) is a service that allows you to quickly craft & send beautiful emails **without ever leaving your code editor** ✨

[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/Templateless)](https://twitter.com/templateless)

- 🚀 Ship faster by writing emails as code
- 🥹 No drag-and-drop builders, no templates, no messing w/ HTML
- 📬 Use your favorite email provider
- 🍺 Start emailing for free

This is all it takes to create an email:

```rust
// Signup confirmation email in Rust 🦀

let email = Email::builder()
  .to(EmailAddress::new("customer@example.com"))
  .subject("Confirm your signup 👋")
  .content(
    Content::builder()
      .text("Please confirm your email address")
      .button("Confirm email", "https://your-company.com/confirm?token=")
      .build()?
  )
  .build()?;
```

Try an SDK — there are lots of components to explore ⬇️
