| Variable |	Description |
|----------|----------------|
|ID	       |идентификатор заявки клиента на кредит|
|year	   |год подачи заявки на кредит|
|loan_limit|указывает, является ли кредит соответствующим лимитам (cf) или несоответствующим (ncf)|
|Gender	   |пол заёмщика (male, female, joint, sex not available)|
|approv_in_adv|	указывает, был ли кредит одобрен заранее (pre, nopre)|
|loan_type |тип кредита (type1, type2, type3)|
|loan_purpose|	цель кредита (p1, p2, p3, p4)|
|Credit_Worthiness |	кредитоспособность заёмщика (l1, l2)|
|open_credit|	указывает, есть ли у заявителя открытые кредитные счета (opc, nopc)|
|business_or_commercial|	указывает, предназначен ли кредит для бизнесса/коммерческих целей (ob/c - - business/commercial, nob/c - personal)|
|loan_amount|	размер кредита|
|rate_of_interest|	процентная ставка по кредиту|
|Interest_rate_spread|	разница между процентной ставкой по кредиту и базовой процентной ставкой|
|Upfront_charges |	это первоначальные сборы, которые взимаются при оформлении кредита, то есть расходы, связанные с получением займа. К таким сборам могут относиться комиссии за рассмотрение заявки, оценка имущества (если это залоговый кредит), услуги нотариуса, страхование и другие платежи, необходимые для оформления и выдачи кредитных средств|
|term |срок кредита в месяцах	|
|Neg_ammortization |	указывает, допускает ли кредит отрицательную амортизацию (neg_amm, not_neg)|
|interest_only |	указывает, есть ли у кредита возможность оплаты только процентов (int_only, not_int)|
|lump_sum_payment |	указывает, требуется ли единовременный платеж в конце срока кредита (lpsm, not_lpsm)|
|property_value |	стоимость финансируемой недвижимости|
|construction_type |	тип здания (sb - site built, mh - manufactured home)|
|occupancy_type |	категория здания по назначению (pr - primary residence, sr- secondary residence, ir - investment property)|
|Secured_by|	тип залога, обеспечивающего кредит (home, land)|
|total_units|	количество юнитов/объектов в финансируемом объекте недвижимости (1U, 2U, 3U, 4U)|
|income|	годовой доход заявителя|
|credit_type|	тип кредита (CIB - credit information bureau , CRIF - CIRF credit - information bureau, EXP - experian , EQUI - equifax)|
|Credit_Score|	кредитный рейтинг заявителя|
|co-applicant_credit_type|	тип кредита созаявителя (CIB - credit information bureau EXP - experian)|
|age |	возраст заёмщика|
|submission_of_application|	указывает, как было подано заявление (to_inst - to institution (в учреждении, лично), - not_inst - not to institution)|
|LTV|	Коэффициент соотношения суммы кредита к стоимости недвижимости, рассчитываемый как сумма кредита, деленная на стоимость недвижимости|
|Region|	географический регион, в котором находится недвижимость (North, south, central, North-East)|
|Security_Type|	тип обеспечения или залога, обеспечивающего кредит(direct, indirect)|
|Status|	указывает, был ли кредит невыплачен (1) или нет (0)|
|dtir1|	соотношение долга к доходу|