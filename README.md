[ReadMe.txt](https://github.com/user-attachments/files/32673657/ReadMe.txt)

Layout

flex --> puts children side by side in a row
grid --> puts children in a grid
md:grid-cols-4 --> 4 columns from tablet and up
md:grid-cols-2 --> 2 columns from tablet and up
md:grid-cols-12 --> 12 columns, used with col-span
md:col-span-5 --> this item takes 5 out of 12 columns
block --> element takes a full line
inline-block --> takes content width but can have size


Alignment

items-center --> centers children vertically
justify-between --> first child left, last child right
justify-center --> centers children horizontally
text-center --> centers the text
mx-auto --> centers the element itself


Spacing

p-4 --> padding all sides
px-12 --> padding left and right
py-16 --> padding top and bottom
pt-14 --> padding top only
pb-8 --> padding bottom only
mb-4 --> margin bottom
mt-12 --> margin top
ml-24 --> margin left
gap-6 --> space between children
space-y-4 --> space between stacked children

Numbers: 1 = 4px, 2 = 8px, 4 = 16px, 6 = 24px, 12 = 48px


Sizing

w-full --> width 100%
w-24 --> fixed width 96px
w-fit --> width fits content only
w-[340px] --> custom width
h-screen --> height of the screen
h-40 --> fixed height 160px
max-w-md --> maximum width, stops it getting too wide
max-w-6xl --> a wider maximum width


Colors

bg-white --> white background
bg-gray-50 --> very light gray background
bg-teal-500 --> teal background
bg-emerald-700 --> dark green background
bg-red-400 --> red background
text-white --> white text
text-gray-600 --> gray text
text-teal-600 --> teal text
border-orange-400 --> orange border color

Higher number = darker. Add /80 for transparency.


Text

text-xs --> very small text
text-sm --> small text
text-lg --> large text
text-2xl --> bigger
text-5xl --> very big
text-[13px] --> custom size
font-bold --> bold
font-semibold --> less bold
font-mono --> typewriter font
leading-6 --> space between lines
leading-relaxed --> comfortable line spacing


Images

object-cover --> image fills its box without stretching
bg-cover --> background image fills the element
bg-center --> background image centered


Borders and Corners

rounded --> slightly rounded corners
rounded-xl --> more rounded
rounded-3xl --> very rounded
rounded-full --> circle or oval
rounded-t-[120px] --> rounded from top only
border-b-4 --> 4px line under the element


Position

relative --> stays in place, lets children position inside it
absolute --> leaves the flow, others move up behind it
inset-0 --> covers the parent completely
z-10 --> puts it above others
overflow-hidden --> cuts off anything sticking out

Rule: parent gets relative, child gets absolute.


Effects

hover:bg-red-500 --> changes background on mouse over
rotate-[-8deg] --> tilts the element
-skew-y-2 --> slants the element
skew-y-2 --> slants it back, used on content so only background stays slanted
scale-110 --> makes it 10% bigger


Responsive

sm: --> from 640px
md: --> from 768px, tablet
lg: --> from 1024px, laptop
xl: --> from 1280px
