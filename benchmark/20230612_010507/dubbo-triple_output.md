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
# Warmup Iteration   1: 2.160 ops/ms
# Warmup Iteration   2: 6.001 ops/ms
# Warmup Iteration   3: 8.547 ops/ms
Iteration   1: 9.219 ops/ms
Iteration   2: 9.175 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.252 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (9.175, 9.252, 9.364), stdev = 0.099
  CI (99.9%): [7.446, 11.059] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 8.856 ops/ms
# Warmup Iteration   3: 9.583 ops/ms
Iteration   1: 9.772 ops/ms
Iteration   2: 9.936 ops/ms
Iteration   3: 9.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.814 ±(99.9%) 1.954 ops/ms [Average]
  (min, avg, max) = (9.734, 9.814, 9.936), stdev = 0.107
  CI (99.9%): [7.860, 11.768] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 8.701 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.408 ops/ms
Iteration   2: 9.217 ops/ms
Iteration   3: 9.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.418 ±(99.9%) 3.762 ops/ms [Average]
  (min, avg, max) = (9.217, 9.418, 9.629), stdev = 0.206
  CI (99.9%): [5.656, 13.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.117 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 7.517 ops/ms
Iteration   1: 8.071 ops/ms
Iteration   2: 7.931 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.044 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (7.931, 8.044, 8.129), stdev = 0.102
  CI (99.9%): [6.181, 9.906] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.004 ms/op
Iteration   1: 3.357 ±(99.9%) 0.012 ms/op
Iteration   2: 3.433 ±(99.9%) 0.004 ms/op
Iteration   3: 3.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (3.357, 3.419, 3.467), stdev = 0.056
  CI (99.9%): [2.392, 4.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.410 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.002 ms/op
Iteration   1: 3.450 ±(99.9%) 0.005 ms/op
Iteration   2: 3.302 ±(99.9%) 0.007 ms/op
Iteration   3: 3.263 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 1.802 ms/op [Average]
  (min, avg, max) = (3.263, 3.338, 3.450), stdev = 0.099
  CI (99.9%): [1.536, 5.140] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.442 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.005 ms/op
Iteration   1: 3.325 ±(99.9%) 0.008 ms/op
Iteration   2: 3.451 ±(99.9%) 0.006 ms/op
Iteration   3: 3.381 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.386 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.325, 3.386, 3.451), stdev = 0.063
  CI (99.9%): [2.233, 4.539] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.439 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.010 ms/op
Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
Iteration   2: 3.890 ±(99.9%) 0.009 ms/op
Iteration   3: 3.933 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.926 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.890, 3.926, 3.953), stdev = 0.032
  CI (99.9%): [3.340, 4.511] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.896 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
Iteration   1: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  20.126 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  22.310 ms/op
                 createUser·p0.9999: 25.501 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  18.645 ms/op
                 createUser·p0.9999: 26.995 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279651
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4520 
    [ 2.500,  5.000) = 268975 
    [ 5.000,  7.500) = 5156 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     27.298 ms/op
     p(99.9990) =     29.086 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.832 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
Iteration   1: 3.320 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  17.659 ms/op
                 existUser·p0.9999: 23.138 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  12.649 ms/op
                 existUser·p0.9999: 27.886 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   3: 3.382 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   2.105 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  11.043 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289721
  mean =      3.310 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11544 
    [ 2.500,  5.000) = 273230 
    [ 5.000,  7.500) = 4231 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     28.060 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.282 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
Iteration   1: 3.641 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  11.108 ms/op
                 getUser·p0.9999: 23.535 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  22.878 ms/op
                 getUser·p0.9999: 29.282 ms/op
                 getUser·p1.00:   31.588 ms/op

Iteration   3: 3.385 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 28.169 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274062
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7177 
    [ 2.500,  5.000) = 257133 
    [ 5.000,  7.500) = 8542 
    [ 7.500, 10.000) = 845 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     13.231 ms/op
     p(99.9900) =     28.331 ms/op
     p(99.9990) =     30.143 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.642 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.014 ms/op
Iteration   1: 3.963 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  21.616 ms/op
                 listUser·p0.9999: 25.852 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  15.538 ms/op
                 listUser·p0.9999: 18.223 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241647
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 232584 
    [ 5.000,  7.500) = 6583 
    [ 7.500, 10.000) = 1560 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     23.817 ms/op
     p(99.9990) =     26.206 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.252 ± 1.806  ops/ms
ClientPb.existUser                       thrpt       3   9.814 ± 1.954  ops/ms
ClientPb.getUser                         thrpt       3   9.418 ± 3.762  ops/ms
ClientPb.listUser                        thrpt       3   8.044 ± 1.863  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 1.027   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 1.802   ms/op
ClientPb.getUser                          avgt       3   3.386 ± 1.153   ms/op
ClientPb.listUser                         avgt       3   3.926 ± 0.586   ms/op
ClientPb.createUser                     sample  279651   3.431 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.023           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.562           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.298           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.327           ms/op
ClientPb.existUser                      sample  289721   3.310 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.550           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.345           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  274062   3.498 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.231           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.588           ms/op
ClientPb.listUser                       sample  241647   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.686           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.817           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.313           ms/op
