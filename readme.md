NOTE: has only been researched on amazon prime
TODO: make mariadb version

data on availability of mouse bait.

attached document is taken from https://www.pestmagazine.co.uk/media/245855/32-33-know-your-poison.pdf, used to create an unbiased kill count.

poisons are identified by the first letter and last letter

relevant math:

data-ppm=50
data-multiplier=data-ppm/product-ppm
kill-mass=data-mass*data-multiplier
total-mass=10*bait-mass(cg)*pack-size*bait-quantity
kill-count=total-mass/kill-mass
cost-per-mouse=cost/kill-count

for easy comparison the kill counts are in their own column so the simplified formula is:

kill-count=(10*bait-mass(cg)*pack-size*bait-quantity)/(data-mass*(50/product-ppm))
cost-per-mouse=cost/kill-count