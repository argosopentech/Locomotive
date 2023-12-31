## Filters

#### char_length
<code>Removes lines outside of a certain character length
</code>
 * min (int) : Minimum length (inclusive)
 * max (int) : Maximum length (inclusive)

#### contains
<code>Removes lines that contain these words
</code>
 * words (list(str)) : List of words

#### digits_ratio
<code>Removes lines when the ratio of numerical characters to the total length of the line
is greather than max.
</code>
 * max (float) : Maximum ratio ( 0.4)

#### digits_sum_mismatch
<code>Removes lines where the sum of the digits between source and target is not the same.</code>

#### duplicates
<code>Remove lines where source is the same as target</code>

#### nonalphanum_count_mismatch
<code>Removes lines where the sum of non-alphanumeric characters between source and target is not the same</code>

#### nonalphanum_ratio
<code>Removes lines when the ratio of non-alphanumeric characters to the total length of the line
is greather than max.
</code>
 * max (float) : Maximum ratio ( 0.4)

#### source_target_ratio
<code>Removes lines when the ratio (len(source) / len(target)) is outside of bounds
</code>
 * min (float) : Lower bound (inclusive)
 * max (float) : Upper bound (inclusive)

#### uppercase_count_mismatch
<code>Removes lines that have a different number of uppercase letters</code>
