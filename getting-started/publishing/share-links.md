# Share links

{% hint style="info" %}
This feature is available on our Pro and Enterprise plans. If you'd like to learn more, check out [our plans.](../../billing-and-admin/plans/#our-pricing-plans)
{% endhint %}

Share your private content with customers and partners without inviting them to your organization by using a secret shareable link!

## Publish as share link

![](<../../.gitbook/assets/Publish – Share Link.png>)

To enable the secret link, open the space or collection you want to share in GitBook. Hit the Publish button and select "Share Link". This will publish the content behind a share link.

Hit the 'Link and domain settings' link in the publish popover to access your share links. Here you can copy, re-generate, or revoke a share link.

![](<../../.gitbook/assets/Share Link Settings.png>)

Once the link is active, a private token is generated within your URL which is unique to your space. By sharing this link it will give non-GitBook users access to your private content in read mode only.

{% hint style="info" %}
**Good to know:** Share links can be [revoked](share-links.md#revoke-a-link) and regenerated at any time.
{% endhint %}

## Permissions

The content will be accessible to **anyone following the link**. Your team members will always be able to access your content from their dashboard.

{% hint style="info" %}
**Tips:** Make sure you share the link only to people you want to share your private content.\
Don't forget you can [revoke](share-links.md#revoke-a-link) a link any time
{% endhint %}

## Revoke a link

The shareable link can be disabled or regenerated by revoking a link. You can see and revoke any previously generated link in the Link settings panel of the Publish settings for your space.\
When you revoke a link, the space will no longer be available to anyone through that link.

{% hint style="warning" %}
**Heads up!** Anyone using the revoked link will no longer have access to your content.
{% endhint %}

## Security

### Privacy of my content is not critical

If you don't have strong privacy and security requirements, we suggest that you keep your space [public and make it unlisted](space-publishing.md#unlisted).

That means your content won't be indexed by search engines, and will not be easily discoverable.

{% hint style="info" %}
**Good to know:** It's an easy-to-setup approach that still allows you to share your documentation with people you need with a cleaner URL.
{% endhint %}

### I need a more secure alternative

To this day, the most secure way to share your content with a private audience is to have them create a GitBook account and join your organization.

This process can be [automated using SSO/SAML](../../advanced-guides/advanced-sharing-and-security/saml.md).

{% hint style="info" %}
**Good to know:** SSO and SAML can be used to create custom authentication for your documentation, but it will require more setup on your end. SSO and SAML are features included in the **Enterprise plan.**
{% endhint %}

Feel free to [reach out to us](mailto:support@gitbook.com) for guidance on the subject.

If you need complete control over access to your public content, you can roll your own backend and use GitBook's [visitor authentication](../../advanced-guides/advanced-sharing-and-security/visitor-authentication.md) feature.