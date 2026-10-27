# Fedimint Card

An experimental JavaCard that holds the spend keys for Fedimint ecash notes and pays by tap.

The card generates each note's key on its own chip and signs the spend when it is tapped at a
till. The till builds the transaction and the federation checks the signature, with no change to
Fedimint's consensus code. A spike in October 2026 showed it on an NXP J3R180 card against a
four-guardian federation.

> **Experimental.** Fedimint Card is a prototype and has had no outside security review. Keep only
> small amounts on a card.

- Site: [fedimintcard.org](https://fedimintcard.org)
- Source: [fedimintcard/fedimintcard](https://github.com/fedimintcard/fedimintcard)
- Built on [Fedimint](https://fedimint.org). Fedimint Card is an independent project.
- Support: [fedimintcard.org/support](https://fedimintcard.org/support) · Privacy: [fedimintcard.org/privacy](https://fedimintcard.org/privacy)
- Contact: hi@fedimintcard.org
