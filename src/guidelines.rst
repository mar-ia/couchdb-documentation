.. Licensed under the Apache License, Version 2.0 (the "License"); you may not
.. use this file except in compliance with the License. You may obtain a copy of
.. the License at
..
..   http://www.apache.org/licenses/LICENSE-2.0
..
.. Unless required by applicable law or agreed to in writing, software
.. distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
.. WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
.. License for the specific language governing permissions and limitations under
.. the License.

.. _guidelines:

==========================================
Style Guidelines for to this Documentation
==========================================

This is the style guidelines for the CouchDB documentation.
The rules are in descending priority.

#. Syntax
    Correct syntax is always a higher priority than style.
    This includes configuration files, HTML responses, the HTML output from
    Sphinx etc.
#. Empty lines
    * One empty line after license.
    * No empty line at the end of the file.
#. Line ending
    * All lines end with \n.
    * No trailing whitespaces.
#. Line length
    * The maximum line length is 80 characters.
    * ``code-blocks`` may break this limit.
#. Encoding
    All files are ``UTF-8``.
#. Indent
    * **text**: 4 spaces
    * **code**: 2 spaces
#. Links
    * All links are relative.
    * Chapters start with an anchor
        .. code-block:: restructuredtext

            .. _guidelines:
#. Style
    * Titles are under and overlined with =
    * Subtitles are underlined with =
    * The amount of = should match tile length.
    * No empty line after note and warning.
        .. code-block:: restructuredtext

            .. note::
                This is a note.
