# Name='SHRADDHA SUNDARESAN'
Contact='Atlanta, GA|404-XXX-XXXX|wekrklndATgmailDOTcom|linkedin.com/in/ekirkland|github.com/e-kirkland'
edu="EDUCATION"
plt.rcParams['font.family'] = 'sans-serif'
plt.rcParams['font.sans-serif'] = 'STIXGeneral'
fig, ax = plt.subplots(figsize=(8.5, 11))
# set background color
ax.set_facecolor('white')
# remove axes
plt.axis('off')
plt.annotate(Name, (.3,.94), weight='bold', fontsize=20)
plt.annotate(Contact, (.18,.906), weight='regular', fontsize=9)

