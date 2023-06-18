# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.514 ops/ms
# Warmup Iteration   2: 3.636 ops/ms
# Warmup Iteration   3: 6.954 ops/ms
Iteration   1: 6.974 ops/ms
Iteration   2: 7.791 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.532 ±(99.9%) 8.821 ops/ms [Average]
  (min, avg, max) = (6.974, 7.532, 7.831), stdev = 0.484
  CI (99.9%): [≈ 0, 16.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.921 ops/ms
# Warmup Iteration   2: 5.696 ops/ms
# Warmup Iteration   3: 8.413 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 8.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.232 ±(99.9%) 2.439 ops/ms [Average]
  (min, avg, max) = (8.103, 8.232, 8.370), stdev = 0.134
  CI (99.9%): [5.793, 10.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.000 ops/ms
# Warmup Iteration   2: 6.354 ops/ms
# Warmup Iteration   3: 7.427 ops/ms
Iteration   1: 7.547 ops/ms
Iteration   2: 7.742 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.728 ±(99.9%) 3.176 ops/ms [Average]
  (min, avg, max) = (7.547, 7.728, 7.895), stdev = 0.174
  CI (99.9%): [4.552, 10.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.979 ops/ms
# Warmup Iteration   2: 5.389 ops/ms
# Warmup Iteration   3: 6.716 ops/ms
Iteration   1: 6.936 ops/ms
Iteration   2: 6.943 ops/ms
Iteration   3: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.920 ±(99.9%) 0.606 ops/ms [Average]
  (min, avg, max) = (6.882, 6.920, 6.943), stdev = 0.033
  CI (99.9%): [6.314, 7.527] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.104 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.009 ms/op
Iteration   1: 4.043 ±(99.9%) 0.006 ms/op
Iteration   2: 3.984 ±(99.9%) 0.013 ms/op
Iteration   3: 3.994 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.007 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.984, 4.007, 4.043), stdev = 0.031
  CI (99.9%): [3.439, 4.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.740 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.010 ms/op
Iteration   1: 3.948 ±(99.9%) 0.008 ms/op
Iteration   2: 3.831 ±(99.9%) 0.005 ms/op
Iteration   3: 3.813 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.864 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (3.813, 3.864, 3.948), stdev = 0.073
  CI (99.9%): [2.533, 5.196] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.369 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.048 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.006 ms/op
Iteration   1: 4.077 ±(99.9%) 0.005 ms/op
Iteration   2: 4.004 ±(99.9%) 0.007 ms/op
Iteration   3: 4.127 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.069 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (4.004, 4.069, 4.127), stdev = 0.062
  CI (99.9%): [2.934, 5.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.418 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.674 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.821 ±(99.9%) 0.013 ms/op
Iteration   1: 4.722 ±(99.9%) 0.011 ms/op
Iteration   2: 4.634 ±(99.9%) 0.014 ms/op
Iteration   3: 4.853 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.737 ±(99.9%) 2.010 ms/op [Average]
  (min, avg, max) = (4.634, 4.737, 4.853), stdev = 0.110
  CI (99.9%): [2.726, 6.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.571 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 5.657 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.600 ±(99.9%) 0.020 ms/op
Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  11.442 ms/op
                 createUser·p0.9999: 42.501 ms/op
                 createUser·p1.00:   44.237 ms/op

Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.938 ms/op
                 createUser·p0.999:  24.405 ms/op
                 createUser·p0.9999: 28.279 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235538
  mean =      4.072 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 222511 
    [ 5.000, 10.000) = 12531 
    [10.000, 15.000) = 212 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 116 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     22.446 ms/op
     p(99.9900) =     41.120 ms/op
     p(99.9990) =     43.951 ms/op
     p(99.9999) =     44.237 ms/op
    p(100.0000) =     44.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.628 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.013 ms/op
Iteration   1: 3.965 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.804 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  23.208 ms/op
                 existUser·p0.9999: 27.318 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 26.308 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 4.094 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   4.692 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  14.516 ms/op
                 existUser·p0.9999: 29.497 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240147
  mean =      3.998 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 227778 
    [ 5.000,  7.500) = 10362 
    [ 7.500, 10.000) = 1357 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.514 ms/op
     p(99.9900) =     28.211 ms/op
     p(99.9990) =     29.688 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.933 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.711 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.015 ms/op
Iteration   1: 4.007 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  23.344 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  16.425 ms/op
                 getUser·p0.9999: 29.164 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  26.706 ms/op
                 getUser·p0.9999: 29.209 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236579
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 224053 
    [ 5.000,  7.500) = 9308 
    [ 7.500, 10.000) = 2325 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     23.476 ms/op
     p(99.9900) =     28.946 ms/op
     p(99.9990) =     30.000 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.697 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.411 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.812 ±(99.9%) 0.017 ms/op
Iteration   1: 4.974 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  24.665 ms/op
                 listUser·p0.9999: 26.696 ms/op
                 listUser·p1.00:   30.441 ms/op

Iteration   2: 4.720 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 21.110 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.754 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199251
  mean =      4.814 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 166316 
    [ 5.000,  7.500) = 28199 
    [ 7.500, 10.000) = 3765 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.319 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.532 ± 8.821  ops/ms
ClientPb.existUser                       thrpt       3   8.232 ± 2.439  ops/ms
ClientPb.getUser                         thrpt       3   7.728 ± 3.176  ops/ms
ClientPb.listUser                        thrpt       3   6.920 ± 0.606  ops/ms
ClientPb.createUser                       avgt       3   4.007 ± 0.568   ms/op
ClientPb.existUser                        avgt       3   3.864 ± 1.332   ms/op
ClientPb.getUser                          avgt       3   4.069 ± 1.135   ms/op
ClientPb.listUser                         avgt       3   4.737 ± 2.010   ms/op
ClientPb.createUser                     sample  235538   4.072 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.399           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.446           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.120           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.237           ms/op
ClientPb.existUser                      sample  240147   3.998 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.514           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  236579   4.053 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.587           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.046           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.036           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.476           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.946           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.147           ms/op
ClientPb.listUser                       sample  199251   4.814 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.726           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.083           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.441           ms/op
