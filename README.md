# c00lRadio

A frontend for Icecast2 servers (with additional support for Libretime stations), featuring a retro/cyberpunk-ish theme.
Made for my own radio stations, but can be used/configured for others (It's in the MIT license, enjoy)!

## Installation

1. This is made for Cloudflare Workers via the Astro.js Cloudflare adapter - it can be modified to use other services like Netlify or Vercel, however!
2. Fork/clone this repository.
3. Log into Cloudflare, go to Compute -> Workers & Pages -> Create application.
4. Connect your GitHub/GitLab account (or upload statically if you aren't using such services).
5. Link the git repository. Make sure to use the "Astro.js" template.
6. Hope for it to compile.
7. If everything went well, you should now have a c00lRadio frontend setup!

## Environment Variables

| Variable                                 | Description                                        | Example                                                                   |
| ---------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------- |
| SERVICE_NAME                             | Sets what the radio station/service is called.     | WPBB PicelBoi Broadcasting                                                |
| SERVICE_DESCRIPTION                      | Sets what the radio station/service's description. | WPBB PicelBoi Broadcasting is a radio station hosted by PicelBoi for fun. |
| ICECAST_SERVER                           | Sets the Icecast server to be used.                | icecast.picelboi.xyz                                                      |
| LIBRETIME\__INSERT MOUNTPOINT HERE_\_API | Sets the Libretime API link.                       | wpbb-radio-1.picelboi.xyz                                                 |
