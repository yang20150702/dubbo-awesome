# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.466 ops/ms
# Warmup Iteration   2: 11.635 ops/ms
# Warmup Iteration   3: 12.065 ops/ms
Iteration   1: 12.393 ops/ms
Iteration   2: 12.340 ops/ms
Iteration   3: 12.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.390 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (12.340, 12.390, 12.437), stdev = 0.049
  CI (99.9%): [11.500, 13.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.617 ops/ms
# Warmup Iteration   2: 12.665 ops/ms
# Warmup Iteration   3: 12.698 ops/ms
Iteration   1: 12.574 ops/ms
Iteration   2: 12.745 ops/ms
Iteration   3: 12.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.685 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (12.574, 12.685, 12.745), stdev = 0.097
  CI (99.9%): [10.923, 14.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.668 ops/ms
# Warmup Iteration   2: 12.089 ops/ms
# Warmup Iteration   3: 12.305 ops/ms
Iteration   1: 12.447 ops/ms
Iteration   2: 12.481 ops/ms
Iteration   3: 12.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.449 ±(99.9%) 0.560 ops/ms [Average]
  (min, avg, max) = (12.419, 12.449, 12.481), stdev = 0.031
  CI (99.9%): [11.888, 13.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.809 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.562 ops/ms
Iteration   1: 10.500 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.581 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (10.500, 10.581, 10.636), stdev = 0.072
  CI (99.9%): [9.270, 11.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
Iteration   3: 2.569 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.563, 2.566, 2.569), stdev = 0.003
  CI (99.9%): [2.518, 2.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.003 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.494 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.476, 2.494, 2.513), stdev = 0.019
  CI (99.9%): [2.154, 2.833] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.511, 2.517, 2.527), stdev = 0.009
  CI (99.9%): [2.354, 2.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.832 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (3.002, 3.009, 3.014), stdev = 0.007
  CI (99.9%): [2.890, 3.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.225 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.765 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.598 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  11.790 ms/op
                 createUser·p0.9999: 13.944 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.606 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  5.876 ms/op
                 createUser·p0.9999: 12.660 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 2.597 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  6.209 ms/op
                 createUser·p0.9999: 10.814 ms/op
                 createUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370028
  mean =      2.592 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 174121 
    [ 2.500,  3.750) = 191318 
    [ 3.750,  5.000) = 3575 
    [ 5.000,  6.250) = 622 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      6.201 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 16.641 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  8.722 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  8.804 ms/op
                 existUser·p0.9999: 12.378 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383905
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 190398 
    [ 2.500,  3.750) = 190638 
    [ 3.750,  5.000) = 2123 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      8.718 ms/op
     p(99.9900) =     14.415 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.789 ms/op
                 getUser·p0.9999: 13.757 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  9.174 ms/op
                 getUser·p0.9999: 13.570 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.225 ms/op
                 getUser·p0.9999: 12.607 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378977
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 185581 
    [ 2.500,  3.750) = 187986 
    [ 3.750,  5.000) = 3933 
    [ 5.000,  6.250) = 829 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      7.889 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.608 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.250 ms/op
                 listUser·p1.00:   11.567 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  10.022 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.402 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.340 ms/op
                 listUser·p0.9999: 12.265 ms/op
                 listUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313787
  mean =      3.057 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 82398 
    [ 2.500,  3.750) = 190192 
    [ 3.750,  5.000) = 34174 
    [ 5.000,  6.250) = 5584 
    [ 6.250,  7.500) = 692 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     12.693 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.390 ± 0.890  ops/ms
ClientPb.existUser                       thrpt       3  12.685 ± 1.763  ops/ms
ClientPb.getUser                         thrpt       3  12.449 ± 0.560  ops/ms
ClientPb.listUser                        thrpt       3  10.581 ± 1.311  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.048   ms/op
ClientPb.existUser                        avgt       3   2.494 ± 0.339   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.163   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.119   ms/op
ClientPb.createUser                     sample  370028   2.592 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.982           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.675           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.201           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.385           ms/op
ClientPb.existUser                      sample  383905   2.498 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.718           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.415           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.072           ms/op
ClientPb.getUser                        sample  378977   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.889           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  313787   3.057 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.402           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.107           ms/op
