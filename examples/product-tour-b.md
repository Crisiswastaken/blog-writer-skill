"Why your product tour is invisible" (written following the v2 skill)

Nobody reads your product tour. I don't mean they skim it. I mean they click through it like a terms-of-service agreement, eyes glazed, finger on the "Next" button before the tooltip finishes rendering.

Look at the data. Not the completion rate — that number lies. Look at step-two drop-off. Look at how many users who "finished" onboarding still submitted a support ticket within 72 hours asking how to do the thing the tour literally walked them through.

They didn't watch.

Product teams hear this and blame the user. Short attention spans, they say. Impatient. Won't read. But that same user sat through a 45-minute sales demo to get here. They read your entire pricing page, including the FAQ. They'll spend twenty minutes configuring Slack notifications but won't spend forty seconds on your tooltip sequence. The attention isn't the problem. The relevance is.

Here's what actually happens when someone builds a product tour. A PM notices activation is slipping. Maybe it's down 8% quarter over quarter, maybe the CEO mentioned it in an all-hands. Someone pulls up Amplitude, draws a circle around the drop-off point, and says: we need onboarding. So they open Appcues or Driver.js or whatever tool the team already pays for. They draw highlight boxes around UI elements. They write tooltip copy that sounds like a patient teacher. They ship it. The Jira ticket gets closed.

The tour works perfectly as a tour.

The problem is that nobody asked for a tour.

The user who just signed up has one question, and it isn't "where is the settings menu." Their question formed in the gap between clicking "Start Free Trial" and landing in your dashboard. It goes something like: can this thing actually do the thing I came here for? That's it. That's the only question that matters in the first two minutes, and your tour isn't answering it. Your tour is showing them the guest bedroom.

I worked with a team last year — analytics platform, mid-market, the kind of product where the dashboard has nine tabs on first login. They'd built a fourteen-step tour. Fourteen steps. The completion rate was 23%, and they were proud of that number because it was up from 19%. We cut it to two steps. Just two: connect your data source, see your first chart. Activation went up 34% in the first month. Not because the product changed. Because the tour stopped pretending it was a campus orientation and started acting like a concierge.

The distinction matters, and I think most product teams get it backwards. A tour says: here are the rooms in this house. A success path says: here's the kitchen, the fridge has food, eat something. One assumes the user wants to understand the product. The other assumes the user wants to accomplish something. The second assumption is almost always right.

There's an instinct to show everything, though. I get it. Every feature was somebody's quarter. The nav redesign took six sprints. The integrations page is genuinely impressive if someone would just look at it. But a new user cannot absorb seven steps of context about a product they haven't committed to yet. They'll click through your checklist at the speed of obligation, retain nothing, and you'll count them as onboarded.

So pick one action. The single thing that makes a new user think "okay, this works." For a project management tool, it's probably creating a task and assigning it to someone. For an email platform, it's sending a test campaign. For a design tool, it might be dragging something onto a canvas and seeing it render. Everything before that moment is setup cost. Everything after is exploration that the user will do on their own, because now they trust that the product delivers.

Timing, too. This part gets overlooked.

A tour that fires immediately on first login is almost always wrong. The user just arrived. They haven't had time to be confused yet, so your help isn't help — it's interruption. The better trigger is the moment of first hesitation. You can approximate this from session recordings: where does the cursor stop moving? Where do users hover without clicking? Where do sessions end? That's where your tour should start. Not at the welcome screen. At the point of friction.

I keep coming back to a line from a designer I used to work with. She'd say: "If you have to explain it, you've already lost." That's a little extreme for complex products — sometimes explanation is genuinely needed. But the spirit is right. The best product tours don't feel like tours. They feel like the product is just... easy to use. The tooltip appears at the moment you were about to get stuck. The empty state tells you what to do instead of showing you a blank page. The first run experience is designed around doing, not watching.

Driver.js is well-documented. Appcues has drag-and-drop templates. The tooling has never been easier. The hard part isn't technical. The hard part is resisting the urge to show someone everything you've built and instead showing them the one thing they need. A user who accomplishes something real in their first session will come back. A user who completed your fourteen-step guided tour and left having done nothing probably won't.

---

*Assumptions: Voice is an opinionated product/UX person with direct experience. Audience is PMs and product designers. Publication context is a product-focused blog or newsletter.*
