gtranslate
==========

/**
* GTranslate - A class to comunicate with Google Translate(TM) Service
*               Google Translate(TM) API Wrapper
*               More info about Google(TM) service can be found on http://code.google.com/apis/ajaxlanguage/documentation/reference.html
* 		This code has o affiliation with Google (TM) , its a PHP Library that allows to comunicate with public a API
*
* This program is free software: you can redistribute it and/or modify
* it under the terms of the GNU General Public License as published by
* the Free Software Foundation, either version 3 of the License, or
* (at your option) any later version.
*
* This program is distributed in the hope that it will be useful,
* but WITHOUT ANY WARRANTY; without even the implied warranty of
* MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
* GNU General Public License for more details.
*
* You should have received a copy of the GNU General Public License
* along with this program.  If not, see <http://www.gnu.org/licenses/>.
*
* @author Jose da Silva <jose@josedasilva.net>
* @since 2009/11/18
* @version 0.7.7
* @licence LGPL v3
*
* <code>
* <?
* require_once("GTranslate.php");
* try{
*	$gt = new Gtranslate;
*	echo $gt->english_to_german("hello world");
* } catch (GTranslateException $ge)
* {
*	echo $ge->getMessage();
* }
* ?>
* </code>
*/
