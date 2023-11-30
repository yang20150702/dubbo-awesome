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
# Warmup Iteration   1: 4.472 ops/ms
# Warmup Iteration   2: 11.513 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.577 ops/ms
Iteration   3: 12.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.556 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (12.541, 12.556, 12.577), stdev = 0.019
  CI (99.9%): [12.216, 12.896] (assumes normal distribution)


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
# Warmup Iteration   1: 8.291 ops/ms
# Warmup Iteration   2: 13.195 ops/ms
# Warmup Iteration   3: 12.950 ops/ms
Iteration   1: 13.242 ops/ms
Iteration   2: 13.257 ops/ms
Iteration   3: 13.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.274 ±(99.9%) 0.803 ops/ms [Average]
  (min, avg, max) = (13.242, 13.274, 13.324), stdev = 0.044
  CI (99.9%): [12.471, 14.078] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.870 ops/ms
# Warmup Iteration   2: 12.558 ops/ms
# Warmup Iteration   3: 12.776 ops/ms
Iteration   1: 12.822 ops/ms
Iteration   2: 12.788 ops/ms
Iteration   3: 12.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.796 ±(99.9%) 0.431 ops/ms [Average]
  (min, avg, max) = (12.777, 12.796, 12.822), stdev = 0.024
  CI (99.9%): [12.365, 13.227] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.715 ops/ms
# Warmup Iteration   2: 10.532 ops/ms
# Warmup Iteration   3: 10.746 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.787 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (10.723, 10.787, 10.830), stdev = 0.057
  CI (99.9%): [9.755, 11.819] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.003 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.497, 2.518, 2.534), stdev = 0.019
  CI (99.9%): [2.178, 2.858] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
Iteration   3: 2.431 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (2.431, 2.432, 2.434), stdev = 0.002
  CI (99.9%): [2.399, 2.465] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (2.495, 2.497, 2.499), stdev = 0.003
  CI (99.9%): [2.452, 2.543] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.956 ±(99.9%) 0.005 ms/op
Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.956, 2.973, 2.988), stdev = 0.016
  CI (99.9%): [2.678, 3.267] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  11.315 ms/op
                 createUser·p0.9999: 13.617 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.365 ms/op
                 createUser·p0.9999: 12.046 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 12.721 ms/op
                 createUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379325
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 182348 
    [ 2.500,  3.750) = 191692 
    [ 3.750,  5.000) = 4208 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     13.141 ms/op
     p(99.9990) =     14.110 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  6.114 ms/op
                 existUser·p0.9999: 18.408 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  6.023 ms/op
                 existUser·p0.9999: 12.370 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  7.468 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392003
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 192354 
    [ 2.500,  3.750) = 196217 
    [ 3.750,  5.000) = 2486 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     19.175 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  5.497 ms/op
                 getUser·p0.9999: 13.252 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.254 ms/op
                 getUser·p0.9999: 11.862 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  6.891 ms/op
                 getUser·p0.9999: 11.436 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390072
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 195745 
    [ 2.500,  3.750) = 189094 
    [ 3.750,  5.000) = 3996 
    [ 5.000,  6.250) = 696 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      7.313 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.358 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 13.494 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 11.240 ms/op
                 listUser·p1.00:   13.746 ms/op

Iteration   3: 2.999 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  10.246 ms/op
                 listUser·p0.9999: 17.771 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319147
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 95966 
    [ 2.500,  3.750) = 184280 
    [ 3.750,  5.000) = 30901 
    [ 5.000,  6.250) = 6389 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     18.246 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.556 ± 0.340  ops/ms
ClientPb.existUser                       thrpt       3  13.274 ± 0.803  ops/ms
ClientPb.getUser                         thrpt       3  12.796 ± 0.431  ops/ms
ClientPb.listUser                        thrpt       3  10.787 ± 1.032  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.340   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.033   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.046   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.294   ms/op
ClientPb.createUser                     sample  379325   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.093           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.141           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  392003   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.667           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.399           ms/op
ClientPb.getUser                        sample  390072   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.313           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.681           ms/op
ClientPb.listUser                       sample  319147   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.843           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.481           ms/op
