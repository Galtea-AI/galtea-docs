# Task

Your task is to create an MDX file and an HTML email containing the changelog of a release. The MDX file will be used to generate the changelog page in the documentation website, and the HTML email will be sent to all users.

The following is an example of an MDX file that contains the changelog of one release:
```mdx
<Update label="2025-04-28" description="Monitorization and UI improvements">
## Monitoring Is Live!

Real-world user interactions with your products can now be fully monitored and analyzed. Using the Galtea SDK, you can trigger evaluations in a production environment and view how different versions perform with real users. [Read more here](/sdk/api/evaluation-task/service#monitoring-user-interactions-in-production).

## Improved Galtea Red Teaming Tests

Our simulation-generated tests have been upgraded—delivering higher-quality outcomes. Red teaming tests can now be directed to validate even more specific aspects of various security standards, such as OWASP, MITRE ATLAS, and NIST. Specifically, we have improved **jailbreak** attacks, in addition to new **financial attacks** and **toxicity** prompts.

## New Analytics Page

A completely redesigned analytics page is now available! It features:
- **Enhanced Filtering Capabilities.**
- **Improved Data Clarity and Layout.**  
  <Frame>
    <img src="/images/changelog/2025-04-28_new-analytics-page.png" alt="New Analytics Image" />
  </Frame>

The new design not only raises the clarity and density of data presentation but also improves your overall user experience.

> And with monitoring active, you can see production evaluation results in real time on this page!

## User Experience Enhancements

We're continuously refining the platform based on your feedback. This week's improvements include:

- **Customizable Evaluation Tasks List:**  
  You can now select which metrics you are interested in, so the evaluation tasks list only shows the ones you need.

- **Enhanced Evaluation List Filtering:**  
  Easily filter evaluations by versions, evaluations, tests and test groups.

- **Enhanced Test List Filtering:**  
  Easily filter tests by its group.

- **Smart Table Sorting:**  
  When you apply a custom sort, the default (usually creation date) is automatically disabled.

<Frame>
    <img src="/images/changelog/2025-04-28_additional-filters.png" alt="Additional Filters" />
</Frame>

Enjoy the improvements!
</Update>
```

This is an example of the HTML email version for the same changelog:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Galtea Update - 2025-04-28</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Geist:wght@100..900&display=swap" rel="stylesheet" />
  </head>
  <body style="margin: 0; padding: 0; text-align: center; font-family: Geist, Poppins, Arial, sans-serif; background-color: #f6f6f5">
    <table role="presentation" width="100%" cellspacing="0" cellpadding="0" border="0">
      <tr>
        <td align="center">
          <table role="presentation" cellspacing="0" cellpadding="0" border="0" style="background-color: #f9f8f4; text-align: left; margin: 20px; padding: 20px; border: 1px solid #e4e4e7; border-radius: 10px; max-width: 600px">
            <tr>
              <td>
                <div style="text-align: center">
                  <a href="https://galtea.ai" target="_blank">
                    <img src="https://galtea.ai/img/galtea_mod.png" style="width: 250px; height: auto" />
                  </a>
                </div>
                <h1 style="color: #171717; font-size: 26px; margin-bottom: 0px">Monitorization and UI Improvements</h1>
                <a style="color: #5286ff; font-size: 12px; text-decoration: none" href="https://docs.galtea.ai/changelog#2025-04-28">2025-04-28</a>

                <br />
                <h3 style="color: #171717">Monitoring Is Live!</h3>
                <p style="color: #171717; font-size: 16px">
                  Real-world user interactions with your products can now be fully monitored and analyzed. Using the Galtea SDK, you can trigger evaluations in a production environment and view how different versions perform with real users.
                  <a href="https://docs.galtea.ai/sdk/api/evaluation-task/service#monitoring-user-interactions-in-production" style="color: #5286ff">Read more here</a>.
                </p>

                <br />
                <h3 style="color: #171717">Improved Galtea Red Teaming Tests</h3>
                <p style="color: #171717; font-size: 16px">
                  Our simulation-generated tests have been upgraded—delivering higher-quality outcomes. Red teaming tests can now validate more specific aspects of standards such as OWASP, MITRE ATLAS, and NIST. We've improved <strong>jailbreak</strong> attacks, and added new
                  <strong>financial attacks</strong> and <strong>toxicity</strong> prompts.
                </p>

                <br />
                <h3 style="color: #171717">New Analytics Page</h3>
                <p style="color: #171717; font-size: 16px">A completely redesigned analytics page is now available! It features:</p>
                <ul style="color: #171717; font-size: 16px">
                  <li><strong>Enhanced Filtering Capabilities</strong></li>
                  <li><strong>Improved Data Clarity and Layout</strong></li>
                </ul>
                <div style="text-align: center; margin: 10px 0">
                  <img src="https://mintlify.s3.us-west-1.amazonaws.com/galtea/images/changelog/2025-04-28_new-analytics-page.png" alt="New Analytics Page" style="max-width: 100%; height: auto; border-radius: 8px" />
                </div>
                <blockquote style="color: #6f6f6e; font-style: italic; font-size: 14px; margin-top: 10px">And with monitoring active, you can see production evaluation results in real time on this page!</blockquote>

                <br />
                <h3 style="color: #171717">User Experience Enhancements</h3>
                <p style="color: #171717; font-size: 16px">We're continuously refining the platform based on your feedback. This week's improvements include:</p>
                <ul style="color: #171717; font-size: 16px">
                  <li><strong>Customizable Evaluation Tasks List:</strong> Show only the metrics you need.</li>
                  <li><strong>Enhanced Evaluation List Filtering:</strong> Filter by versions, evaluations, tests, and test groups.</li>
                  <li><strong>Enhanced Test List Filtering:</strong> Filter tests by their group.</li>
                  <li><strong>Smart Table Sorting:</strong> Automatically disables default sorting when custom sorting is applied.</li>
                </ul>
                <div style="text-align: center; margin: 10px 0">
                  <img src="https://mintlify.s3.us-west-1.amazonaws.com/galtea/images/changelog/2025-04-28_additional-filters.png" alt="Additional Filters" style="max-width: 100%; height: auto; border-radius: 8px" />
                </div>

                <br />
                <p style="color: #171717; font-size: 16px">Enjoy the improvements!</p>
                <p style="color: #171717; font-size: 16px"><strong>We'd love to hear your thoughts</strong> on these new features. Just reply to this email or ping us in the Slack or Discord channels.</p>

                <hr style="margin-top: 40px; width: 20%; border: 1px solid #e4e4e7" />

                <h3 style="color: #171717; margin-top: 40px">Coming Next</h3>
                <p style="color: #171717; font-size: 16px">We're not stopping here! Soon you'll see new capabilities on the analytics page:</p>
                <ul style="color: #171717; font-size: 16px">
                  <li><strong>Radar View:</strong> A visual comparison of metrics to quickly assess model performance.</li>
                  <li><strong>Time Frame Filtering:</strong> Filter analytics data by date ranges to track progress over time.</li>
                </ul>
                <p style="margin-top: 35px; color: #171717; font-size: 16px">Stay tuned!</p>
                <p style="margin-left: 35px"><strong> - Galtea Team</strong></p>
              </td>
            </tr>
          </table>
        </td>
      </tr>
    </table>
  </body>
</html>
```
Use the above example as a reference to create a new MDX file and HTML email for the following changelog. Also consider the already created changelog files in the project as reference and create links of interest between documentation pages so the users reading the changelog can easily navigate to related content.

The MDX file must use the same components, formatting, tone, style, and link density as the example provided and the rest of changelogs in the project.

The HTML must be very simple. It will be probably read through GMAIL, so it needs to be fully compatible. Use the example above as a very close reference, changing as little as possible.

> Note that the "coming next" section must only appear in the HTML email, not in the MDX file.

Use the current date as the date for the changelog.

Before providing the output files: 
 - If the "coming next" section has not been provided in the changelog, request it from the user.
 - Ask for clarification if any change is unclear.

At the end of the message, after providing the files, you must provide a list of the images that must be uploaded to the server, including a very short description and the path (with the file name) where they should be uploaded. Example: *Screenshot of the New Analytics Page: 2025-04-28_new-analytics-page.png*

The following are the change notes for this release. You can re-write them to seem more natural, appealing and easier to read, but without changing the meaning nor the core information.

## Changelog:
 - Conversations can be simulated to evaluate multi-turn interactions with the product.
 - New metric: Resilience to Noise
 - A new and improved credits management system that now includes warnings when approaching allocated credit limits.
 - New format for sending whole conversations to the galtea platform aligned with OpenAI's messages format.
## Coming Soon:
 - Generation of Synthetic User-Scenarios for test cases
 - Simplification of the usage of custom metrics and custom scores via the sdk