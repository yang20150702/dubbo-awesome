# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 5.561 ops/ms
# Warmup Iteration   3: 8.619 ops/ms
Iteration   1: 9.209 ops/ms
Iteration   2: 9.173 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.296 ±(99.9%) 3.344 ops/ms [Average]
  (min, avg, max) = (9.173, 9.296, 9.507), stdev = 0.183
  CI (99.9%): [5.952, 12.640] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.744 ops/ms
# Warmup Iteration   2: 8.585 ops/ms
# Warmup Iteration   3: 9.215 ops/ms
Iteration   1: 9.878 ops/ms
Iteration   2: 9.751 ops/ms
Iteration   3: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.684 ±(99.9%) 4.273 ops/ms [Average]
  (min, avg, max) = (9.424, 9.684, 9.878), stdev = 0.234
  CI (99.9%): [5.411, 13.957] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.862 ops/ms
# Warmup Iteration   2: 8.302 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 9.473 ops/ms
Iteration   3: 9.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.329 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (9.224, 9.329, 9.473), stdev = 0.129
  CI (99.9%): [6.973, 11.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.787 ops/ms
# Warmup Iteration   2: 6.790 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.003 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (7.832, 8.003, 8.120), stdev = 0.151
  CI (99.9%): [5.249, 10.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.402 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.006 ms/op
Iteration   1: 3.438 ±(99.9%) 0.004 ms/op
Iteration   2: 3.449 ±(99.9%) 0.007 ms/op
Iteration   3: 3.349 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.412 ±(99.9%) 1.003 ms/op [Average]
  (min, avg, max) = (3.349, 3.412, 3.449), stdev = 0.055
  CI (99.9%): [2.409, 4.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.055 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.007 ms/op
Iteration   1: 3.263 ±(99.9%) 0.009 ms/op
Iteration   2: 3.334 ±(99.9%) 0.007 ms/op
Iteration   3: 3.384 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.327 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.263, 3.327, 3.384), stdev = 0.061
  CI (99.9%): [2.218, 4.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.635 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.005 ms/op
Iteration   1: 3.442 ±(99.9%) 0.007 ms/op
Iteration   2: 3.325 ±(99.9%) 0.010 ms/op
Iteration   3: 3.414 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (3.325, 3.394, 3.442), stdev = 0.061
  CI (99.9%): [2.284, 4.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.743 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.012 ms/op
Iteration   1: 4.132 ±(99.9%) 0.006 ms/op
Iteration   2: 4.020 ±(99.9%) 0.009 ms/op
Iteration   3: 3.888 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.013 ±(99.9%) 2.223 ms/op [Average]
  (min, avg, max) = (3.888, 4.013, 4.132), stdev = 0.122
  CI (99.9%): [1.790, 6.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.892 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
Iteration   1: 3.402 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.634 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   2: 3.443 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  22.974 ms/op
                 createUser·p0.9999: 26.556 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.646 ms/op
                 createUser·p0.999:  17.003 ms/op
                 createUser·p0.9999: 25.472 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280887
  mean =      3.412 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8167 
    [ 2.500,  5.000) = 268026 
    [ 5.000,  7.500) = 3623 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     17.972 ms/op
     p(99.9900) =     25.917 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.884 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  11.146 ms/op
                 existUser·p0.9999: 26.579 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   2: 3.294 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  15.940 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 27.960 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293016
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16774 
    [ 2.500,  5.000) = 270434 
    [ 5.000,  7.500) = 4973 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.585 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     13.974 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     28.815 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.454 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
Iteration   1: 3.316 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  19.349 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.483 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  20.284 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  22.877 ms/op
                 getUser·p0.9999: 28.470 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282327
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6302 
    [ 2.500,  5.000) = 268973 
    [ 5.000,  7.500) = 6072 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     19.552 ms/op
     p(99.9900) =     26.454 ms/op
     p(99.9990) =     28.984 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.191 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.013 ms/op
Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  19.957 ms/op
                 listUser·p0.9999: 28.256 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 4.113 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  16.684 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234484
  mean =      4.090 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 225722 
    [ 5.000,  7.500) = 5847 
    [ 7.500, 10.000) = 2031 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     16.287 ms/op
     p(99.9900) =     26.447 ms/op
     p(99.9990) =     31.113 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.296 ± 3.344  ops/ms
ClientPb.existUser                       thrpt       3   9.684 ± 4.273  ops/ms
ClientPb.getUser                         thrpt       3   9.329 ± 2.356  ops/ms
ClientPb.listUser                        thrpt       3   8.003 ± 2.754  ops/ms
ClientPb.createUser                       avgt       3   3.412 ± 1.003   ms/op
ClientPb.existUser                        avgt       3   3.327 ± 1.109   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 1.110   ms/op
ClientPb.listUser                         avgt       3   4.013 ± 2.223   ms/op
ClientPb.createUser                     sample  280887   3.412 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.686           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.972           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.787           ms/op
ClientPb.existUser                      sample  293016   3.276 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.585           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.492           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  282327   3.401 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.552           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.454           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  234484   4.090 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.513           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.447           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.457           ms/op
