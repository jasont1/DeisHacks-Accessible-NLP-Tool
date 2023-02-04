<div class="relative flex w-[calc(100%-50px)] flex-col gap-1 md:gap-3 lg:w-[calc(100%-115px)]">
<div class="flex flex-grow flex-col gap-3">
<div class="min-h-[20px] flex flex-col items-start gap-4 whitespace-pre-wrap">
<div class="markdown prose w-full break-words dark:prose-invert light">
<h1>DeisHacks: Accessible NLP Tool</h1>
<h2>Introduction</h2>
<p>We are a team participating in the DeisHack, a hackathon for social good. Our project is an accessible tool that uses natural language processing and OpenAI's Generative Pre-trained Transformer 3 (GPT-3) model to extract important information from long-form text, such as reports from non-profit organizations.</p>
<h2>Problem Statement</h2>
<p>Analyzing lengthy reports produced by non-profit organizations can be a time-consuming and costly process, especially for organizations with limited resources. These reports often contain valuable information and statistics, but extracting this information can be challenging and highly labor-intensive&nbsp;due to the reports' length and format. No automation currently exists for this problem.<br /><br />For example: The Clipper Foundation receives updates from their grant recipient in a standardized<strong> long-answer format</strong>: The Philanthropy MA Common Proposal Form.&nbsp;<br /><br /><strong>100s of Non-Profits</strong> use formats like the Philanthropy MA Common Proposal Form, which ultimately needs to be <strong>manually analyzed</strong>.&nbsp;<br /><br />Here are some examples of questions in this form:&nbsp;</p>
<ol>
<li>What were your primary impacts and other major accomplishments?</li>
<li>How did you determine your progress and measure your impact?</li>
<li>Describe any setbacks encountered during the period of this grant and how they were addressed.</li>
</ol>
These 10+ page reports are currently looked through by hand and manually analyzed.<br /><br />
<h2>Solution</h2>
<p>Our tool aims to automate the manual process of analyzing reports by using the GPT-3 model for NLP analysis. The user inputs the report into the tool, and the tool processes the report using the GPT-3 model to extract important information, including statistics, and formats it into a markdown table.<br /><br />Rather than changing the format of these reports on a case-by-case basis, our solution works to save time and resources for any non-profit struggling with this problem.</p>
<h2>Key Features</h2>
<ul>
<li>Easy-to-use input interface</li>
<li>Utilization of OpenAI's GPT-3 model for NLP analysis</li>
<li>Automated extraction of statistics and important information</li>
<li>Output presents data in a clear, easily readable format for easy analysis</li>
<li>Ability to take long-answer questions and convert them into a markdown table format</li>
</ul>
<h2>Getting Started</h2>
<p>To use our tool:</p>
<ol>
<li>Clone the repository from Github.</li>
<li>Install the required dependencies (listed in the "Dependencies" section).</li>
<li>Run the tool</li>
<li>Access the tool by accessing its interface on a local server</li>
<li>Input the report | document | form | proposal into the tool.</li>
<li>View the output&nbsp;</li>
</ol>
<h2>Dependencies</h2>
<ul>
<li>OpenAI's GPT-3 API</li>
</ul>
<h2>Conclusion</h2>
<p>In conclusion, our tool is designed to help non-profit organizations streamline the analysis of lengthy reports. With its utilization of OpenAI's GPT-3 model for NLP analysis, automated extraction of key information, and clear markdown table format for output, our tool has the potential to save organizations time, effort, and resources. Our hope is that this tool will contribute to the ongoing efforts towards social justice and equality, by making the process of report analysis more efficient and accessible for non-profits. We are confident that this solution will make a positive impact for non-profits and are excited to see the positive change it can bring.</p>
</div>
</div>
</div>
<div class="flex justify-between">
<div class="text-gray-400 flex self-end lg:self-center justify-center mt-2 gap-3 md:gap-4 lg:gap-1 lg:absolute lg:top-0 lg:translate-x-full lg:right-0 lg:mt-0 lg:pl-2 visible"><button class="p-1 rounded-md hover:bg-gray-100 hover:text-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-gray-200 disabled:dark:hover:text-gray-400"> &lt;/button &gt;</button><button class="p-1 rounded-md hover:bg-gray-100 hover:text-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-gray-200 disabled:dark:hover:text-gray-400"> </button></div>
</div>
</div>
