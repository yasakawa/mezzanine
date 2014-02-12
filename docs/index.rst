=========
Mezzanine
=========

.. note::
    本ドキュメントはMezzanine 3.0のドキュメントを日本語訳したものです。
    元データはGitHub (https://github.com/yasakawa/mezzanine) で管理しています。

..
    Welcome to the Mezzanine project. To learn more about Mezzanine please
    read the :doc:`overview` which contains a feature list, installation
    guide and other general information. To get an idea of the types of
    sites possible with Mezzanine, have a look at the `gallery of sites
    powered by Mezzanine <http://mezzanine.jupo.org/sites/>`_.
..
Mezzanineプロジェクトへようこそ。Mezzanineについてもっと学ぶには、
機能一覧やインストール手順、そして一般的な情報を含む :doc:`overview` をお読みください。
Mezzanineでどのような種類のサイトが実現可能かのアイデアを得るためには、
`Mezzanine利用サイトのギャラリー <http://mezzanine.jupo.org/sites/>`_ をご覧ください。

.. note::

..
    A working knowledge of `Django <https://www.djangoproject.com/>`_
    is required to work with Mezzanine and the documentation assumes as
    much. If you're new to Django, you'll need to work through the
    `Django tutorial <https://docs.djangoproject.com/en/dev/intro/tutorial01/>`_
    before being able to understand the concepts used throughout the
    Mezzanine documentation. *A mantra for working with Mezzanine:
    Mezzanine Is Just Django* - `Ken Bolton <http://bscientific.org/>`_,
    long-time Mezzanine contributor.
..
Mezzanineでの作業やドキュメントは、Django <https://www.djangoproject.com/>`_
の作業知識を前提としています。もしあなたが初めてDjangoに触れる場合は、
Mezzanineのドキュメントで使用されるコンセプトを理解しようとする前に
`Djangoチュートリアル <https://docs.djangoproject.com/en/dev/intro/tutorial01/>`_
を一通り実施する必要があるでしょう。*Mezzanineでの作業の際のマントラは
まさにDjangoと同じなのです* - `Ken Bolton <http://bscientific.org/>`_,
古くからのMezzanineコントリビュータ.

..
    **Front-end developers** can read about how to set up templates for
    specific :doc:`device-handling` such as phones and tablets. Mezzanine
    also comes with the ability for content authors to edit content directly
    within a page while viewing it on the website. You can read about this
    and how to implement this feature within templates under
    :doc:`inline-editing`.
..
**フロントエンド開発者** 携帯電話やタブレットのような特定の
:doc:`device-handling` の設定方法について知ることができます。
Mezzanineはコンテンツ管理者がサイト上でページを参照している際に
直接そのコンテンツを編集することもできます。
この機能についてや、テンプレート内でのその実装方法については
:doc:`inline-editing` で参照することができます。

**Back-end developers** can get a better technical overview of how
content is managed and how to customize Mezzanine in general by
reading about Mezzanine's :doc:`content-architecture` which describes
the main components and how to extend them with your own custom
content types, or by reading about :doc:`model-customization` for
implementing more low-level customizations as required. There is also
a section on the :doc:`admin-customization` provided by Mezzanine, as
well as a :doc:`model-graph` depicting the relationships between all
the models.

**System administrators** can find out about some of the production
requirements and operations in the :doc:`deployment` and
:doc:`caching-strategy` sections.

**Further reading** includes :doc:`frequently-asked-questions`,
:doc:`utilities`, a section on :doc:`user-accounts`,
information about Mezzanine's :doc:`search-engine`, and a section
on Mezzanine's :doc:`configuration` which outlines the various settings
for configuring Mezzanine. Lastly, you can learn about
:doc:`blog-importing` into Mezzanine, or just browse the auto-generated
docs for each of Mezzanine's :doc:`packages`.

Table Of Contents
=================

.. toctree::
    :maxdepth: 2

    overview
    content-architecture
    model-customization
    admin-customization
    utilities
    model-graph
    device-handling
    inline-editing
    caching-strategy
    deployment
    frequently-asked-questions
    user-accounts
    search-engine
    configuration
    blog-importing
    packages
    colophon
