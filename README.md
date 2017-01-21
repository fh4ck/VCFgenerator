# VCFgenerator
Visit Card File generator (32-bit and 64-bit Windows)

> **Disclaimer:**

> - This tool is created for the sole purpose of security awareness and education, it should not be used against systems that you do not have permission to test.

> - If you do not fully understand how this tool should be used, please don't download / use it.

> - Refer to the laws in your province / country and of the province / country involved in the use of this tool, before accessing, using,or in any other way utilizing it.

> - Neither administration of this server, the authors of this material, or anyone else affiliated in any way, is going to accept responsibility for your actions.

## Basic usage

In many countries, mobile phones are assigned dedicated mobile phone codes within the country's telephone numbering plan. Some countries that do not use area codes (e.g. Singapore) allocate specific number ranges to mobile phones that are easily distinguishable from landlines. One notable exception to this type of assignment is how the countries within the North American Numbering Plan (the United States and its territories, Canada, and much of the Caribbean) assign mobile phones subscriber numbers within geographic area codes by not being easily distinguishable from landlines.

VCGgenerator may produce an output according to the standard mentioned above, where the following parameters are entered correctly:

Parameter     | Expected value (Please refer to the [International prefixes table](https://en.wikipedia.org/wiki/List_of_mobile_phone_number_series_by_country#International_prefixes_table))
-------- | ---
Country Name | Mnemonic name of the country your are going to create numbering to (will be used as phone book field)
International Calling code | **+** symbol followed by **digit**(s)
Mobile Prefix | The original prefix issued to the [mobile network operator](https://en.wikipedia.org/wiki/List_of_mobile_phone_number_series_by_country#cite_note-prefix_note-1)
National Significant Number | [NSN](https://en.wikipedia.org/wiki/List_of_mobile_phone_number_series_by_country#cite_note-nsn_note-2)
Iteration Number | Amount of numbers to be inserted into the Visit Card File, starting from the given parameters (value must be numeric and greater than 1)

Once executed the binary will produce a .vcf file ready to be imported in your device.

--
Fh4ck
