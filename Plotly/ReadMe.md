Data visualization using Plotly


> To use Plotly in Google Colab, run the following function and call it at every cell to run.
> def configure_plotly_browser_state():
>  import IPython
>  display(IPython.core.display.HTML('''
>        <script src="/static/components/requirejs/require.js"></script>
>        <script>
>          requirejs.config({
>            paths: {
>              base: '/static/base',
>              plotly: 'https://cdn.plot.ly/plotly-latest.min.js?noext',
>            },
>          });
>        </script>
>        '''))
