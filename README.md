This is a snippet collection intended to provide me (and anyone learning C#) a quick way to generate common structures, like lists, arrays, sets, tuples, and dictionaries.

It's a slightly approach to the larger csharp-snippets repo. This one doesn't offer types in the snippet shortcut, but instead just preselects the generic types to be filled in.

Variable name placeholder is preselected for renaming.
Types (T, or T1, T2 for tuples, or TKey, TValue for dictionaries) are also preselected for renaming.

Snippet examples and what they produce:

narr
T[] placeholder = [];

ndic
Dictionary<TKey, TValue> placeholder = [];

nlst
List<T> placeholder = [];

nque
Queue<T> placeholder = new();

nset
HashSet<T> placeholder = new();

nstk
Stack<T> placeholder = new();

ntup
(T1, T2) placeholder = default;

varr
var placeholder = new T[] { };

vdic
var placeholder = new Dictionary<TKey, TValue>();

vlst
var placeholder = new List<T>();

vque
var placeholder = new Queue<T>();

vset
var placeholder = new HashSet<T>();

vstk
var placeholder = new Stack<T>();

vtup
var placeholder = default((T1, T2));
