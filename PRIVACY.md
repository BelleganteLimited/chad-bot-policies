# Chad Bot — Privacy Policy

Last updated: **November 3, 2026**. This policy takes effect when published.  
Operator responsible for this application: **the Chad Bot project**  
Privacy, correction and deletion requests: **[Chad Bot support](https://github.com/BelleganteLimited/chad-bot-policies/issues/new)**  
Discord application ID: **1567104075386851329**

This policy covers the private Discord PAPER application: interpretation of selected trading-source messages and charts, simulated trade decisions, and private reports. It does not describe Discord's own service or every separate trading system run by the operator. Some features are still in development. Historical records can remain stored while collection is stopped.

## Information handled

- **Source material:** selected message text, embeds, charts and other acquired attachments; server, channel, message and author identifiers and labels; links, reply references, publication/edit/observation times, content hashes, versions and recorded coverage gaps. Text or images may themselves contain personal information. Capturing evidence does not prove its accuracy or its author's permission for a different use.
- **Interpretations and PAPER records:** extracted trading instructions, source quotations and image references, model/provenance records, decisions, simulated orders and fills, and private reporting/delivery history.
- **Connection and security records:** application/account identifiers, requested or granted scopes, authorization-attempt results, grant expiry and technical audit records. If authorization succeeds, the application can retain OAuth access and returned refresh tokens in restricted local files. Earlier browser session state remains retained locally; it is not a source from which this OAuth flow extracts tokens. The new flow does not persist authorization codes or copy the client secret into its grant records.
- **Support requests:** information you choose to send to the operator when asking for help or exercising a data right.

## Purposes and recipients

Information is used to preserve source context, interpret trading ideas, prevent duplicate or contradictory simulated actions, recover interrupted work, investigate errors and produce private PAPER reports.

When configured and enabled, Anthropic's API receives selected source text, referenced message identifiers and chart images with associated attachment metadata for AI inference. Content can contain identifiers within the text or image itself. The application uses inference, not model training. Anthropic describes its commercial API's default training treatment in its [commercial-data guidance](https://privacy.claude.com/en/articles/7996868-is-my-data-used-for-model-training); this policy does not promise zero provider retention or confirm account-specific exceptions/settings.

Discord handles authorization and, when enabled, receives reports through the operator's configured private reporting destination. People able to access that destination can read its reports. The operator and authorized maintainers may access retained records for operation, support and incident investigation. Necessary hosting/service providers may process data on the operator's behalf; disclosure may also be required by law. The application has no advertising or sale-of-source-data feature. It does not publish the source archive as part of these policy pages.

## Retention and security

Source versions, acquired images, derived results and audit/recovery records are stored locally. The current intake has no automatic time-based deletion; retained evidence and backups are not erased simply because a source message is edited or deleted, access expires, or Discord authorization is revoked. Deletion requests currently require manual handling across source records, derived stores and backups; automatic comprehensive erasure has not been verified. We do not promise a fixed automatic deletion period. Engineering or audit preferences do not override applicable deletion obligations.

Access to connection credentials is restricted using local file ownership and permissions, and the authorization flow excludes credential values from its public result. These measures do not establish encryption at rest across all stored records or backups; that protection has not been verified. Security requirements must be resolved before enabling affected processing. No system can promise absolute security.

## Your choices and requests

Contact [Chad Bot support](https://github.com/BelleganteLimited/chad-bot-policies/issues/new) to ask what information the application holds about you, request correction or deletion, or report unauthorized processing. **That tracker is public.** Start with a minimal request such as “I need private help with a privacy or deletion request.” Do not post your Discord identifiers, private message links, source content, account details or credentials. The project will arrange an appropriate private channel before requesting the information reasonably needed to find the material and verify that it concerns you. The operator will review requests and address applicable correction or deletion obligations; any legally required retention must be distinguished from ordinary engineering or audit preferences.

Stopping collection or revoking the application's authorization in Discord prevents use of that authorization but does not automatically delete existing records. The operator must address applicable deletion obligations; the incomplete deletion implementation described above is not an exemption from those obligations.

The application is not intended to collect private financial credentials, personal account statements, health data or other sensitive personal information. Please report accidental inclusion so it can be addressed. The public policy/support pages themselves are hosted by GitHub, which handles visitors and support submissions under its [Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Changes to data categories, recipients or purposes require an updated dated policy before that changed processing begins.

See [Discord's Privacy Policy](https://discord.com/privacy). Questions about this application's handling should go to the operator contact above, rather than being treated as a request to Discord itself.
