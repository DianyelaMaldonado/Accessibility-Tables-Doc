# Typical Layout Table Accessibility:

A very simple web accessibility guide for Tables about navigating on the keyboard and small tips for responsiveness, I hope it is useful to you ♥️.

#### Keyboard navigation (VoiceOver):
VoiceOver must be on and on the table press the following:

    ctrl + option + command + shift T
    
#### Responsive Table:
If the table is responsive, it is not enough to set on the table container `overflow ="auto"`, we must keep in mind ***keyboard support:***


> We need to make the scrollable element focusable so it can be
> operated by keyboard. That’s just a case of adding `tabindex="0"`. But
> since screen reader users will be able to focus it too, we need to
> provide some context for them.
> 
> In this case, I’ll use the table’s `<caption>` to label the scrollable
> region using `aria-labelledby`.
> 
>-Explanation taken from the book of Inclusive components by Heydon Pickering.
>
In short, it is to make the table focusable when the container overflows the table.


#### 📎 Ref:
 1. [W3.org Tables Tutorial](https://www.w3.org/WAI/tutorials/tables/).
 2. Book Inclusive Components Heydon Pickering - 11 Data tables.
 3. Tables with screen readers [Video](https://www.youtube.com/watch?v=tlpQ0d2ADNo).
 4. [Accessibility guidance](https://not-checklist.intopia.digital/#:~:text=%C2%A04.1.3-,Tables,-Tables%20help%20people).

-Dianyela Maldonado.
 Web Developer. 👩🏻‍💻
