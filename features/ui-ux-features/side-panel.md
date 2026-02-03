# The Side Panel – a Magic Multitool for In-depth Expertise

## Overview

In our everyday work, we constantly juggle large amounts of information. 
When working with a business system, this often means switching back and forth between multiple screens just to gather the data needed for a single task. 
This kind of friction in daily workflows costs both time and mental energy. 
But there is a way to smooth things out.  

In ERP.net, there is a powerful multitool that enables users to perform a wide range of precise actions based on the content they are working with at any given moment — seamlessly and without disruption. 
The side panel is a UI element — typically appearing on the right side — that provides additional contextual tools and information related to the selected record, document, or entity.

The side panel is like a magician’s wand: its behavior changes based on where you are in the system and what is the user’s role.
It offers a variety of functions — most of them tailored to the current context. 
Hard to picture? 
Think of it as a Swiss army knife that contains tens of useful tools, all hidden - one can use one or few of these depending on the object and the intention.

![Side_panel_001-](https://github.com/user-attachments/assets/8bb89e80-a9d8-434b-b59c-314f3ccda6f9)
_What you see here: The side panel shows up on the right side to provide additional tools for dealing with the information from the current navigator._ 

## How the side panel works

In our daily work with digital systems, we are accustomed to the so-called right-click — on the right side, within easy reach of our hand, there is a whole palette of additional tools that allow us to perform a wide range of operational actions. The Side Panel builds on this "right-side" logic.

The Side Panel becomes available at the right side when a user accesses data records through any navigator — for example, when entering the Sales, Orders, or Customers navigator, or any other navigator within ERP.net. 
Also the Side Panel is accessible when a specific record is opened, such as an invoice, offer, or project. 
In both cases, it can be opened via the kebab-menu (three-dot menu) on the right.

The functions available in the side panel vary depending on the context. 
They are navigator-specific which means they appear - and are applicable - to the current content only.

For instance, when a user opens an Offer, the side panel allows him to review the whole Document Flow — documents before/after the current one in the document chain (e.g., offer → sales order → shipment/invoice), when such relations exist.
And if the user opens a Case that’s part of a Project, the side panel conveniently suggests viewing the Case Hierarchy right away.

![Side_panel_003-](https://github.com/user-attachments/assets/ab6cb569-cfb6-40c8-bdcd-5e1b955e1f55)
_What you see here: Some of the tools inside the side panel are specific to the type of entry the user is dealing  with, e.g. when a Case is open, the side panel would serve the “Meet” tool and the “Case hierarchy” tool; one would not see these functions when opening an invoice or a customers profile._ 

There are, however, some common types of tools within the side panel that may appear identical in every scenario. 
But don’t be misled — although they share the same names and functions, their results vary depending on the context. 
For example:

__Discussion__: The side panel lets you open a discussion that is related to the item you’re viewing. 
Each time, it’s a different discussion. 
If you’ve opened a specific Offer, the side panel will lead to the discussion thread for that particular Offer. 
Open another offer, and the panel will instead show the conversation related to the new one.

__To-do items__: Most entries in ERP.net allow the creation of to-do tasks. 
When viewing a Case, for example, the side panel will display to-do items associated with that particular Case. 
But if you’re viewing a Lead record, the to-dos shown will relate specifically to the particular Lead.

Other tools that share the same name but deliver context-specific results include Notifications, Files, etc. 

![Side_panel_005-](https://github.com/user-attachments/assets/fbb4bdfd-c545-42c2-9fde-0ab76fa580d2)
_What you see here: some of the tools in the side panel look the same, e.g. Discussion,To-do, etc._ 
_They perform the same action, but over different object – the one that is open on screen._ 
_So the result is different every time_. 

Basically what Side Panel is doing is:

1. It saves time (fewer clicks, less navigation)

Without a side panel:

You open a Sales Order,

Then open the Customer,

Then open their Invoices,

Then go back again…

With the Side Panel:

All that related information is already there

You stay on the same screen

Result: less switching, faster execution

2. It gives context when you need it

ERP screens usually show only the current document.
The Side Panel answers questions like:

Has this customer overdue invoices?

Is this product in stock?

Is this order already shipped or paid?

Result: You make decisions with context, not guesses.

3. It reduces mistakes

Many ERP errors happen because users:

Miss important information

Don’t notice related problems (credit limits, blocked customers, missing stock)

The Side Panel can:

Show balances, availability, and statuses

Surface risks before you confirm or post

Result: Fewer costly mistakes.

4. It supports different roles without clutter

Not everyone needs the same data:

Sales → customer history, pricing, credit

Logistics → availability, shipments

Finance → payments, balances

Instead of:

Overloading the main screen

ERP.net uses the Side Panel to:

Show role-specific information

Keep the main form clean and simple

5. It enables “next action” thinking

The Side Panel doesn’t just show data — it suggests what you can do next:

Create invoice

Create shipment

Open related document

Continue workflow

Result: The system guides the user, not just stores data.

6. It scales with complexity

As your business grows:

More documents

More checks

More dependencies

The Side Panel scales without redesigning screens by:

Adding insights

Adding relations

Adding automation hooks


## Lists vs. Single Entries

Side panel behaves slightly differently when the user is watching a list inside a navigator and when the user is dealing with a individual record inside a form. 

Whenever there’s a large list of items — such as a list of Leads or Orders for instance — the side panel options will suggest some actions that are only possible over bigh amount s of records.
And there’s a good reason for that.

What do people typically do with lists? 
They often search for specific types of entries. 
That’s why, when in a list navigator, the side panel includes an Advanced Filter. 
This powerful tool allows users to search using one or multiple criteria they define. 
The Advanced filter usually comes on top of the side panel toolkit along with several common instruments.

![Side_panel_004--](https://github.com/user-attachments/assets/cd1656b2-9a3a-49c1-8e7b-82a4cadfb753)
_What you see here: The Advanced filter is one of the most powerful tools one can find inside the “side panel” toolbox._

After using the Advanced filter the user may end up with a selection of items to continuously work on. 
In case the user walts to preserve the selection, the Side Panel makes this possible through the “Create a Tile” option _(read more about [Tiles](https://info.erp.net/features/my-apps/tiles.html)")_.

![Side_panel_006-](https://github.com/user-attachments/assets/966339db-776e-431c-afa2-50e9fdd3838f)
_What you see here: When the user is dealing with a selection of items from a list, the Side Panel will suggest creating a new Tile._

When viewing single entries — such as a certain Lead, an Order, or a Case — the side panel offers different options. 
For example, one can add the entry to Favorites, or save it as a document within a specific Folder (read more about Folders). 

In essence, the side panel displays __context-specific information and tools__ related to the selected product, party, or person, or other kind of entry – or the selected list of entries. 
It’s somewhat like right-clicking on a webpage: a contextual menu appears, offering actions that depend on what you’ve selected.

__Main benefit__: The side panel enhances usability — it is a one-click-away drawer full of functional tools that let the user work easily within one screen, being able to do almost everything with the information in front.  
Hence, the Side panel allows the user to get the maximum of the ERP.net toolset. 

[!Note]
Note: The side panel operates independently of the main form view. 
This means you can keep the main form open on the screen and the side panel will appear on the right, allowing you to view all the important details without losing context.

### Additional Information or Actionable Tools

Some of the tools within the side panel are designed simply to add more context and information to the data that is already visible on screen. 
For example, the Notifications, System Info, and Details tools provide additional insights related to the object currently displayed.

Other tools, however, are actionable — they allow the user to interact, to make changes, to produce results. 
For instance, Discussion lets users participate in a chat about a specific entry, ask questions to colleagues, or leave comments. 
The Delete and Change History tools, whenefer they appear, are self-explanatory, enabling users to remove items or review modification logs.

![Side_panel_007-](https://github.com/user-attachments/assets/2e06b69e-5f28-4517-95f3-9f04e1f8ed79)
_What you see here: About half of the side panel tools are actionable and allow the user to perform different actions to the record._

## Verdict: The Side Panel – What You Get 

ERP.net's side panel is a powerful multitool that enhances user productivity by embedding different tools directly within the workspace, depending on the specific content that is currently viewed. 
This allows for: 

___Faster access___: Rather than opening several forms or going back and forth, one can see all the key information in the side panel.

___Better usability___: Data and tools are  intuitively accessible and one-click away. 

___Enhanced navigation___: Especially in lists/navigators, the side panel gives extra information without leaving the list, pluss alowing to keep preselected items or lists to ease the future work. 
