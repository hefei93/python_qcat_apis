# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

# Test function to print out all list items in list recursively
def printOutAllListItems(curList):

# Function to print out the value of strItem in a well formatted list
# curList: <List> List to find out the value
# strItem: <string> matching string used to find the value
# length: <int> the number of list elements after the matching string of strItem
# example: printOutListItemValue(curList,"featureGroupIndRel10-v1060",4) will return '00000000 00101000 00000000 00000000'B
def printOutListItemValue(curList, strItem, length=1):

def printOutFGIValue(curList, strItem, length=1):

# use qcat client to merge multiple logs into single
# input: a string with all logs path combined together
#        could be qmdl, isf, dlf, qmdl2, even mixed. for now will support only 1 format at a time.
# output: path to save the merged log.
#        could be isf, dlf, TXT; details see QCAT6 User Guide <<80-V1233-6 T>>
def qcat_merge_log(targetLogPath, mergedLogPath, filterList = None):

# Use qcat to parse log file into TXT
# logpath: path of log to be parsed
# filterList: special mask IDs in a line to be filtered out, example: 0x147E
# parsedFile: output txt
def qcat_parse_log(logpath, filterList, parsedFile):

# Use qcat to parse log file into TXT
# logpath: path of log to be parsed
# filterList: special mask IDs in a line to be filtered out, example: 0x147E
# parsedFile: output txt
def qcat_filter_log(logpath, filterList, parsedFile):

# test for another method, specific for "UECapabilityInformation"
def qcat_parse_per_log_package(logpath, filterID, filterStr, parsedFile):

# filter special lines contain a list of words, example: ["l_PgaGain", "q_AdcAmpIp1mV"]
def findandsavelogs(substr, infile, outfile):

def getTimeListFromLog(logfile):

# find out words contains time format string, example: '20:56:13.945',
# and return the list of time
def getTimeFromLog(logfile, id):

# find out words contains a value after a name example: q_AdcAmpIp1mV = 111,
# and return the list of value
def getSpecialPointFromLog(logfile, id):

