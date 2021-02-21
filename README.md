<p align="center">
  <img src="https://user-images.githubusercontent.com/2182637/53611918-54c1ff80-3c24-11e9-9917-66ac3cef513d.png" alt="react beautiful dnd logo" />
</p>
<h1 align="center">react-beautiful-dnd <small><sup>(rbd)</sup></small></h1>

<div align="center">

**Όμορφο** και **προσιτό** drag και drop για λίστες με [`React`](https://facebook.github.io/react/)

[![CircleCI branch](https://img.shields.io/circleci/project/github/atlassian/react-beautiful-dnd/master.svg)](https://circleci.com/gh/atlassian/react-beautiful-dnd/tree/master)
[![npm](https://img.shields.io/npm/v/react-beautiful-dnd.svg)](https://www.npmjs.com/package/react-beautiful-dnd)

![Παράδειγμα εφαρμογής](https://user-images.githubusercontent.com/2182637/53614150-efbed780-3c2c-11e9-9204-a5d2e746faca.gif)

[Παίξε αν θες με το παράδειγμα!](https://react-beautiful-dnd.netlify.com/iframe.html?selectedKind=board&selectedStory=simple)

</div>

## Κύρια χαρακτηριστικά

- Όμορφη και [φυσική κίνηση](/docs/about/animations.md) των αντικειμένων 💐
- [Προσιτό](/docs/about/accessibility.md): δυναμική υποστήριξη πληκρολογίου και ανάγνωσης οθόνης ♿️
- [Εξαιρετική επίδοση](/docs/support/media.md) 🚀
- Καθαρό και ισχυρό api που θα το βρει απλό κάποιος που θα αρχίσει να ασχολείται μαζί του
- Εκτελείται εξεραιτικά καλά με απλές αλληλεπιδράσεις ενός φυλλομετρητή
- [Ανώνυμο στυλ](/docs/guides/preset-styles.md)
- Χωρίς δημιουργία επιπλέον περικαλλύματος για κόμβους του dom - flexbox και φιλικό σε διαχείρηση εστίασης!

## Ξεκίνα από εδώ 👩‍🏫

Έχουμε δημιουργήσει [ένα δωρεάν μάθημα στο `egghead.io` 🥚](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd) για να σε βοηθήσουμε να ξεκινήσεις με `react-beautiful-dnd` όσο το δυνατόν γρηγορότερα.

[![course-logo](https://user-images.githubusercontent.com/2182637/43372837-8c72d3f8-93e8-11e8-9d92-a82adde7718f.png)](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)

## Προσωρινά υποστηριζόμενο σύνολο χαρακτηριστικών ✅

- Κάθετες λίστες ↕
- Οριζόντιες λίστες ↔
- Κίνηση μεταξύ λιστών (▤ ↔ ▤)
- [Υποστήριξη εικονικής λίστας 👾](/docs/patterns/virtual-lists.md) - ξεκλείδωμα 10,000 αντικειμένων @ 60fps
- [Συνδυασμός αντικειμένων](/docs/guides/combining.md)
- Υποστήριξη για ποντίκι 🐭, πληκτρολόγιο 🎹♿️ και αφή 👉📱 (κινητό, tablet..) 
- [Υποστήριξη για πολλαπλό drag](/docs/patterns/multi-drag.md)
- Απίστευτη υποστήριξη σε ανάγνωση οθόνης ♿️ - παρέχουμε εκπληκτική εμπειρία σε εργαλεία ανάγνωσης οθόνης στα αγγλικά. Παρέχουμε επιπλέον πλήρη παραμετροποίηση ελέγχων και διεθνή υποστήριξη σε αυτούς που τη χρειάζονται 💖
- [Υποθετικό dragging](/docs/api/draggable.md#optional-props) και [υποθετικό dropping](/docs/api/droppable.md#conditionally-dropping)
- Πολλαπλές ανεξάρτητες λίστες σε μια σελίδα
- Ελαστικά μεγέθη αντικειμένων - τα draggable αντικείμενα μπορούν να έχουν διαφορετικά ύψη (κάθετες λίστες) ή πλάτη (οριζόντιες λίστες)
- [Πρόσθεσε και αφαίρεσε αντικείμενα κατα τη διάρκεια ενός drag](/docs/guides/changes-while-dragging.md)
- Συμβατότητα με σημασιολογική αναταξινόμηση `<table>` - [πρότυπα table](/docs/patterns/tables.md)
- [Αυτόματο scrolling](/docs/guides/auto-scrolling.md) - αυτόματο scroll των κιβωτίων και του παραθύρου όπως απαιτείται κατά τη διάρκεια ενός drag (ακόμα και με πληκτρολόγιο 🔥)
- Παραμετροποίηση χειρισμού drag - μπορείς να κάνεις drag ένα ολόκληρο αντικείμενο ή ένα μέρος του.
- Δυνατότητα να μετακινήσεις ένα drag αντικείμενο σε ένα άλλο αντικείμενο ενώ κάνεις drag - [Αλλαγή προγόνου `<Draggable />`](/docs/guides/reparenting.md)
- [Δημιουργία σεναρίου για drag και drop εμπειριών 🎮](/docs/sensors/sensor-api.md)
- Επιτρέπει επεκτάσεις για να υποστηρίζουν [οποιαδήποτε είσοδο θέλεις 🕹](/docs/sensors/sensor-api.md)
- 🌲 Υποστήριξη δένδρου μέσω [`@atlaskit/tree`](https://atlaskit.atlassian.com/packages/confluence/tree) πακέτου
- Μια `<Droppable />` λίστα μπορεί να είνα ένα scroll κιβώτιο (χωρίς πατέρα που κάνει scroll) ή να είναι παιδί ενός scroll κιβωτίου (αυτό επίσης δεν έχει πατέρα που κάνει scroll)
- Ανεξάρτητες εμφωλευμένες λίστες - μία λίστα μπορεί να είνα παιδί μια άλλης λίστας, αλλά δεν μπορείς να κάνεις drag σε αντικείμενα από μια λίστα πατέρα σε μια λίστα παιδί
- Συμβατότητα εμφάνισης στην πλευρά εξυπηρετητή (SSR) - δες [resetServerContext()](/docs/api/reset-server-context.md)
- Εκτελείται σωστά με [εμφωλευμένα διαδραστικά αντικείμενα](/docs/api/draggable.md#interactive-child-elements-within-a-draggable-) βάσει προτύπου

## Κίνητρο 🤔

`react-beautiful-dnd` υπάρχει για να δημιουργεί όμορφο drag και drop για λίστες που οποιοσδήποτε μπορεί να χρησιμοποιήσει - ακόμη και άνθρωποι που δεν βλέπουν. Για μια καλή ανασκόπηση της ιστορίας και του κινήτρου της εργασίας, μπορείς να δεις αυτές τις εξωτερικές πηγές:

- 📖 [Επανεξέταση drag και drop](https://medium.com/@alexandereardon/rethinking-drag-and-drop-d9f5770b4e6b)
- 🎧 [React podcast: γρήγορο, προσβάσιμο και όμορφο drag και drop](https://reactpodcast.simplecast.fm/17)

## Όχι για όλους ✌️

Υπάρχουν πολλές βιβλιοθήκες που επιτρέπουν drag και drop διαδράσεις στη React. Η πιο αξιοσημείωτη είναι η [`react-dnd`](https://github.com/react-dnd/react-dnd). Μπορεί να κάνει απίστευτη δουλειά στο να παρέχει ένα σπουδαίο σύνολο από drag και drop πρωτόγονα που δουλεύουν ειδικά καλά με [άγρια ασυνέπεια](https://www.quirksmode.org/blog/archives/2009/09/the_html5_drag.html) html5 drag και drop χαρακτηριστικό. `react-beautiful-dnd` είναι υψηλού επιπέδου αφαίρεση ειδικά φτιαγμένο για λίστες (κάθετη, οριζόντια, κίνηση μεταξύ λιστών, εμφωλευμένες λίστες..). Μέσα σε αυτό το υποσύνο λειτουργιών  η`react-beautiful-dnd` προσφέρει μια ισχυρή, φυσική και όμορφη εμπειρία drag και drope. Ωστόσο, δεν μπορεί να παρέχει το πλάτος των λειτουργιών που παρέχονται από τη `react-dnd`. Οπότε η `react-beautiful-dnd` μπορεί να μην είναι για εσένα, εξαρτάται για την περίπτωση που το θέλεις.

## Τεκμηρίωση 📖

### Σχετικά 👋

- [Εγκατάσταση](/docs/about/installation.md)
- [Παραδείγματα και δείγματα](/docs/about/examples.md)
- [Ξεκίνα από εδώ](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)
- [Αρχές σχεδίασης](/docs/about/design-principles.md)
- [Κινούμενα σχέδια](/docs/about/animations.md)
- [Προσβασιμότητα](/docs/about/accessibility.md)
- [Υποστήριξη φυλλομετρητή](/docs/about/browser-support.md)

### Αισθητήρες 🔉

> Οι τρόποι με τους οποίους κάποιος μπορεί να ξεκινήσει και να ελέγχει ένα drag

- [Drag με ποντίκι 🐭](/docs/sensors/mouse.md)
- [Drag με αφή 👉📱](/docs/sensors/touch.md)
- [Drag με πληκτρολόγιο 🎹♿️](/docs/sensors/keyboard.md)
- [Δημιούργησε το δικό σου αισθητήρα](/docs/sensors/sensor-api.md) (επιτρέπει κάθε τύπο εισόδου αν είναι εμπειρία σεναρίου)

### Διεπαφή Προγραμματισμού Εφαρμογών 🏋️‍

![διάγραμμα](https://user-images.githubusercontent.com/2182637/53607406-c8f3a780-3c12-11e9-979c-7f3b5bd1bfbd.gif)

- [`<DragDropContext />`](/docs/api/drag-drop-context.md) - _Τυλίγει το κομμάτι της εφαρμογής που θέλεις να έχει ενεργοποιημένο το drag και drop_
- [`<Droppable />`](/docs/api/droppable.md) - _Μια περιοχή που μπορεί να γίνει drop. Περιέχει `<Draggable />`s_
- [`<Draggable />`](/docs/api/draggable.md) - _Σε τι μπορεί να γίνει drag_
- [`resetServerContext()`](/docs/api/reset-server-context.md) - _Χρησιμότητα εμφάνισης στην πλευρά εξυπηρετητή (SSR)_

### Οδηγίες 🗺

- [`<DragDropContext />` ανταποκριτές](/docs/guides/responders.md) - _`onDragStart`, `onDragUpdate`, `onDragEnd` και `onBeforeDragStart`_
- [Συνδυάζει τα `<Draggable />`](/docs/guides/combining.md)
- [Συνήθη προβλήματα εγκατάστασης](/docs/guides/common-setup-issues.md)
- [Χρησιμοποιώντας `innerRef`](/docs/guides/using-inner-ref.md)
- [Ρύθμιση ανίχνευσης προβλημάτων και αποκατάσταση σφαλμάτων](/docs/guides/setup-problem-detection-and-error-recovery.md)
- [Κανόνες για `draggableId` και `droppableId`s](/docs/guides/identifiers.md)
- [Διατήρηση εστίασης προγράμματος περιήγησης](/docs/guides/browser-focus.md)
- [Προσαρμογή ή παράλειψη των κινούμενων σχεδίων](/docs/guides/drop-animation.md)
- [Αυτόματο scrol](/docs/guides/auto-scrolling.md)
- [Έλεγχος της οθόνης ανάγνωσης](/docs/guides/screen-reader.md)
- [Χρήση html5 `doctype`](/docs/guides/doctype.md)
- [`TypeScript` και `flow`: τύπος πληροφορίας](/docs/guides/types.md)
- [Drag σε `<svg>`](/docs/guides/dragging-svgs.md)
- [Αποφυγή τρεμοπαίγματος της εικόνας](/docs/guides/avoiding-image-flickering.md)
- [Μη ορατά προεπιλεγμένα στυλ](/docs/guides/preset-styles.md)
- [Πώς εντοπίζουμε τα δοχεία κύλισης](/docs/guides/how-we-detect-scroll-containers.md)
- [Πώς χρησιμοποιούμε τα συμβάντα dom](/docs/guides/how-we-use-dom-events.md) - _Useful if you need to build on top of `react-beautiful-dnd`_
- [Προσθέτοντας `<Draggable />`κατα τη διάρκεια ενός drag (11.x behaviour)](/docs/guides/changes-while-dragging.md) - _⚠️ Προχωρημένα
- [Ρύθμιση πολιτικής ασφάλειας περιεχομένου](/docs/guides/content-security-policy.md)

### Πρότυπα 👷‍

- [Εικονικές λίστες 👾](/docs/patterns/virtual-lists.md)
- [Πολλαπλό drag](/docs/patterns/multi-drag.md)
- [Πίνακες](/docs/patterns/tables.md)
- [Αλλαγή πατέρα σε `<Draggable />`](/docs/guides/reparenting.md) - _Χρησιμοποιώντας το δικό μας αντίγραφο διεπαφής προγραμματισμού εφαρμογών ή τη δική μας πύλη_

### Υποστήριξη 👩‍⚕️

- [Μηχανική υγεία](/docs/support/engineering-health.md)
- [Κοινότητα και πρόσθετα](/docs/support/community-and-addons.md)
- [Δημοσίευση σημειώσεων και αρχείου αλλαγών](https://github.com/atlassian/react-beautiful-dnd/releases)
- [Αναβάθμιση](/docs/support/upgrading.md)
- [Βήματα](https://github.com/atlassian/react-beautiful-dnd/issues)
- [Μέσα μαζικής ενημέρωσης](/docs/support/media.md)

## Διάβασέ το σε άλλες γλώσσες 🌎

- [![us](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/United-States.png) **English**](https://github.com/atlassian/react-beautiful-dnd)
- [![kr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/South-Korea.png) **한글/Korean**](https://github.com/LeeHyungGeun/react-beautiful-dnd-kr)
- [![ru](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Russia.png) **На русском/Russian**](https://github.com/vtereshyn/react-beautiful-dnd-ru)
- [![pt](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Brazil.png) **Português/Portuguese**](https://github.com/dudestein/react-beautiful-dnd-pt)

## Συγγραφέας ✍️

Alex Reardon [@alexandereardon](https://twitter.com/alexandereardon)

## Συνεργάτες 🤝

- Bogdan Chadkin [@IAmTrySound](https://twitter.com/IAmTrySound)
- Luke Batchelor [@alukebatchelor](https://twitter.com/alukebatchelor)
- Jared Crowe [@jaredjcrowe](https://twitter.com/jaredjcrowe)
- Πολλοί άλλοι [@Atlassian](https://twitter.com/Atlassian)'s!
