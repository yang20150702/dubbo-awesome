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
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 5.955 ops/ms
# Warmup Iteration   3: 8.709 ops/ms
Iteration   1: 8.909 ops/ms
Iteration   2: 9.353 ops/ms
Iteration   3: 9.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.163 ±(99.9%) 4.176 ops/ms [Average]
  (min, avg, max) = (8.909, 9.163, 9.353), stdev = 0.229
  CI (99.9%): [4.987, 13.339] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 9.774 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 9.842 ops/ms
Iteration   3: 10.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.886 ±(99.9%) 2.103 ops/ms [Average]
  (min, avg, max) = (9.799, 9.886, 10.017), stdev = 0.115
  CI (99.9%): [7.783, 11.989] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 8.844 ops/ms
# Warmup Iteration   3: 8.862 ops/ms
Iteration   1: 9.495 ops/ms
Iteration   2: 9.774 ops/ms
Iteration   3: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.538 ±(99.9%) 3.965 ops/ms [Average]
  (min, avg, max) = (9.346, 9.538, 9.774), stdev = 0.217
  CI (99.9%): [5.573, 13.503] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 7.090 ops/ms
# Warmup Iteration   3: 7.831 ops/ms
Iteration   1: 8.310 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.097 ±(99.9%) 3.377 ops/ms [Average]
  (min, avg, max) = (7.977, 8.097, 8.310), stdev = 0.185
  CI (99.9%): [4.719, 11.474] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.604 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.010 ms/op
Iteration   1: 3.479 ±(99.9%) 0.004 ms/op
Iteration   2: 3.398 ±(99.9%) 0.007 ms/op
Iteration   3: 3.359 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.412 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.359, 3.412, 3.479), stdev = 0.061
  CI (99.9%): [2.300, 4.524] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.298 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.006 ms/op
Iteration   1: 3.266 ±(99.9%) 0.007 ms/op
Iteration   2: 3.300 ±(99.9%) 0.005 ms/op
Iteration   3: 3.222 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.263 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.222, 3.263, 3.300), stdev = 0.039
  CI (99.9%): [2.549, 3.977] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.002 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.005 ms/op
Iteration   1: 3.468 ±(99.9%) 0.007 ms/op
Iteration   2: 3.509 ±(99.9%) 0.009 ms/op
Iteration   3: 3.458 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.479 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.458, 3.479, 3.509), stdev = 0.027
  CI (99.9%): [2.984, 3.973] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.462 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.807 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.009 ms/op
Iteration   1: 4.014 ±(99.9%) 0.008 ms/op
Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
Iteration   3: 3.847 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.931 ±(99.9%) 1.526 ms/op [Average]
  (min, avg, max) = (3.847, 3.931, 4.014), stdev = 0.084
  CI (99.9%): [2.406, 5.457] (assumes normal distribution)


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
# Warmup Iteration   1: 8.991 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
Iteration   1: 3.466 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  19.324 ms/op
                 createUser·p0.9999: 22.734 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.450 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  20.883 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  19.634 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274880
  mean =      3.490 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10420 
    [ 2.500,  5.000) = 257550 
    [ 5.000,  7.500) = 5826 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     19.632 ms/op
     p(99.9900) =     24.232 ms/op
     p(99.9990) =     26.133 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.852 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
Iteration   1: 3.310 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  14.867 ms/op
                 existUser·p0.9999: 20.524 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.472 ms/op
                 existUser·p0.9999: 21.907 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 26.938 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289696
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13296 
    [ 2.500,  5.000) = 271775 
    [ 5.000,  7.500) = 4026 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     26.217 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 8.555 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.010 ms/op
Iteration   1: 3.528 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  20.429 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  22.359 ms/op
                 getUser·p0.9999: 33.325 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  15.884 ms/op
                 getUser·p0.9999: 25.914 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278707
  mean =      3.444 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8863 
    [ 2.500,  5.000) = 259980 
    [ 5.000,  7.500) = 8879 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     16.862 ms/op
     p(99.9900) =     31.933 ms/op
     p(99.9990) =     34.420 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 9.965 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
Iteration   1: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  20.935 ms/op
                 listUser·p0.9999: 25.591 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 3.907 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 15.866 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.892 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.267 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244275
  mean =      3.932 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 235941 
    [ 5.000,  7.500) = 6320 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 366 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     23.808 ms/op
     p(99.9990) =     25.974 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.163 ± 4.176  ops/ms
ClientPb.existUser                       thrpt       3   9.886 ± 2.103  ops/ms
ClientPb.getUser                         thrpt       3   9.538 ± 3.965  ops/ms
ClientPb.listUser                        thrpt       3   8.097 ± 3.377  ops/ms
ClientPb.createUser                       avgt       3   3.412 ± 1.112   ms/op
ClientPb.existUser                        avgt       3   3.263 ± 0.714   ms/op
ClientPb.getUser                          avgt       3   3.479 ± 0.495   ms/op
ClientPb.listUser                         avgt       3   3.931 ± 1.526   ms/op
ClientPb.createUser                     sample  274880   3.490 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.452           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.632           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.232           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  289696   3.312 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.973           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.296           ms/op
ClientPb.getUser                        sample  278707   3.444 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.684           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.862           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.933           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  244275   3.932 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.104           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.808           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.608           ms/op
