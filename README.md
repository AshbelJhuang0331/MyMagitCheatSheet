<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Magit</a>
<ul>
<li><a href="#sec-1-1">1.1. Installation</a></li>
<li><a href="#sec-1-2">1.2. Hotkey</a></li>
<li><a href="#sec-1-3">1.3. Reference</a></li>
</ul>
</li>
</ul>
</div>
</div>


# Magit<a id="sec-1" name="sec-1"></a>

It's just my cheat sheet of magit.

## Installation<a id="sec-1-1" name="sec-1-1"></a>

M-x package-install RET magit RET

## Hotkey<a id="sec-1-2" name="sec-1-2"></a>

Combination key prefix meaning:
-   M : Alt
-   C : Ctrl
-   RET: Return / Enter
-   SPC: Space

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="left" />

<col  class="left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="left">Command</th>
<th scope="col" class="left">Hotkey</th>
</tr>
</thead>

<tbody>
<tr>
<td class="left">Check git status under magit</td>
<td class="left">M-x magit-status RET</td>
</tr>


<tr>
<td class="left">Refresh magit status buffer</td>
<td class="left">g</td>
</tr>


<tr>
<td class="left">Quit windows</td>
<td class="left">q</td>
</tr>


<tr>
<td class="left">Check actions</td>
<td class="left">?</td>
</tr>


<tr>
<td class="left">Expand/Collapse staged/unstaged changes/commits</td>
<td class="left">tab</td>
</tr>


<tr>
<td class="left">Collapse changes/commits</td>
<td class="left">1</td>
</tr>


<tr>
<td class="left">Expand changes/commits</td>
<td class="left">4</td>
</tr>


<tr>
<td class="left">Collapse all</td>
<td class="left">M-1</td>
</tr>


<tr>
<td class="left">Expand all</td>
<td class="left">M-4</td>
</tr>


<tr>
<td class="left">Next/Previous line</td>
<td class="left">n / p</td>
</tr>


<tr>
<td class="left">Next/previous</td>
<td class="left">M-n / M-p</td>
</tr>


<tr>
<td class="left">Enlarge/Shrink hunk</td>
<td class="left">+ / -</td>
</tr>


<tr>
<td class="left">Reset hunk size to default</td>
<td class="left">0</td>
</tr>


<tr>
<td class="left">Open remote menu</td>
<td class="left">M</td>
</tr>


<tr>
<td class="left">Open fetch menu</td>
<td class="left">f</td>
</tr>


<tr>
<td class="left">Open pull menu</td>
<td class="left">F</td>
</tr>


<tr>
<td class="left">Open push menu</td>
<td class="left">P</td>
</tr>


<tr>
<td class="left">Open merge menu</td>
<td class="left">m</td>
</tr>


<tr>
<td class="left">Stage/Unstage file</td>
<td class="left">s / u</td>
</tr>


<tr>
<td class="left">Discard change</td>
<td class="left">k</td>
</tr>


<tr>
<td class="left">Open commit menu</td>
<td class="left">c</td>
</tr>


<tr>
<td class="left">Extend the current commit HEAD</td>
<td class="left">e</td>
</tr>


<tr>
<td class="left">Amend the commit message</td>
<td class="left">a</td>
</tr>


<tr>
<td class="left">Reword commit message</td>
<td class="left">r</td>
</tr>


<tr>
<td class="left">Fixup/Squash the current commit</td>
<td class="left">f / s</td>
</tr>


<tr>
<td class="left">Access log menu</td>
<td class="left">l</td>
</tr>


<tr>
<td class="left">Reset to selected commit</td>
<td class="left">x</td>
</tr>


<tr>
<td class="left">Revert the commit</td>
<td class="left">v</td>
</tr>


<tr>
<td class="left">Diff between selected commit and working tree</td>
<td class="left">d</td>
</tr>


<tr>
<td class="left">Apply the selected commit's change to working tree</td>
<td class="left">a</td>
</tr>


<tr>
<td class="left">Cherry pick the commit on top of working tree</td>
<td class="left">A</td>
</tr>


<tr>
<td class="left">Interactively rebase from HEAD to selected commit</td>
<td class="left">E</td>
</tr>


<tr>
<td class="left">Copy the commit hash:</td>
<td class="left">C-w</td>
</tr>


<tr>
<td class="left">Show the full commit message</td>
<td class="left">SPC</td>
</tr>
</tbody>
</table>

P.S. Usually used hotkeys
1.  `l l` or `l h` see git log.
2.  `f a` fetch from all remotes.
3.  `F p` pull from remotes.
4.  `c c` write commit message, then use `C-c C-c` to commit.
5.  `P p` push to remotes.

## Reference<a id="sec-1-3" name="sec-1-3"></a>

[An introduction to Magit, an Emacs mode for Git - Mickey Peterson](https://www.masteringemacs.org/article/introduction-magit-emacs-mode-git)

[Magit Official Site](https://magit.vc/)