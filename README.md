Copyright (c) 2008-2014, Sine Nomine Associates
All rights reserved.

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

--------------------------------------------------------------------

This directory contains various programs that maybe useful
for sites running OpenAFS.

admin/              - misc afs scripts
  afs-vol-check     - check for volume inconsistencies
  afs-get-versions  - report server versions
  afs-vol-paths     - process output of volscan
  afs-read-audit    - example sysvmq audit reader

debug/              - debugging tools
  cachestat         - report what is cached for certain files
  ciread            - read data from CacheItems
  cisearch          - search CacheItems for a file
  dirobj            - decode afs directory objects
  vixlink           - check volinfo output for cross-device link
  volnamei          - convert volume numbers to fileserver namei paths

monitor/            - monitoring and related
  cw_graphify.pl    - graph rx calls waiting for thread
  snips             - `snips' plugin for afs

