# 100 Days of code
a personal log by `dylan!`
---

## Day 0

Set up basic template for https://github.com/baltimoreblacktechies/100daysOfCode !
I have ideas for how to extend this based off previous work I've done.

## Day 1

Today I went to a Coffee and Code meetup at spark. I didn't really work too
much during the time, but someone put me on to an [interview question](https://gitlab.com/enlighten-challenge/alphabet-soup) which
they said couldn't be solved in a line of code. Lol, saying you **can't** do
something is a sure-fire way of getting me to do it. Here's my line:

```js
const ALPHABET_SOUP=p=>((nxn,...P)=>((_,
m,W,A)=>W.map(w=>((f,v,e)=>console.log(w
,(L=c=>f((Z=(a,b)=>A(a,(_,i)=> Array(b).
fill(i)))(x,y))[e][c]+":"+(f(T(Z(y,x)))[
e][c]))(v),L(v+w.length-1)))(...[[m=>m],
[ R= m=>m                      .map(r=>[
...r]["r"                      +"everse"
]())],[T=m=>m.map((_,i)=>m.map(a=>a[i]))
],[R,T],[D=m=>A(s=y+x-1,(_,i)=>A(x,(_ ,j
)=>(m[s-i              -j-1] ||[] )[j]).
map(x=> x              !=undefined?x:' '
))],[D,R]    ,[R,D],[R,D,R]].reduce((k,F
)=>k?k:(N    =(f=q=>F.reduce((a,b)=>b(a)
,q) )(m).    reduce((c,r,i)=> c?c : (l =
r.join(''                      ).indexOf
(w))>=0?[                      l,i]:0,0)
)?[f, ...N]:0,0))))([x,y]=nxn.split('x')
.map(p=>parseInt(p)) ,P.slice(0,x ).map(
x=>x.split(' ')),P.slice(x),(d,Q)=>Array
(d ).fill().map(Q) ))(...p.split( '\n'))
```

even formatted into the company's logo! just run `ALPHABET_SOUP`.

## Day 2

Today I set up `nginx` for my home computer since I've migrated to nix.
I went from like 6 config files to 1. See the relevant file here:
https://github.com/dmadisetti/.dots/blob/template/nix/machines/common/nginx.nix

---

# You got this. The above is just a sample.
