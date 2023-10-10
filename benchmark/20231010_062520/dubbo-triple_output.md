# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.013 ops/ms
# Warmup Iteration   2: 5.231 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 8.849 ops/ms
Iteration   2: 8.743 ops/ms
Iteration   3: 9.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.889 ±(99.9%) 3.106 ops/ms [Average]
  (min, avg, max) = (8.743, 8.889, 9.076), stdev = 0.170
  CI (99.9%): [5.784, 11.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.757 ops/ms
# Warmup Iteration   2: 8.646 ops/ms
# Warmup Iteration   3: 9.262 ops/ms
Iteration   1: 8.851 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.103 ±(99.9%) 4.793 ops/ms [Average]
  (min, avg, max) = (8.851, 9.103, 9.375), stdev = 0.263
  CI (99.9%): [4.310, 13.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.005 ops/ms
# Warmup Iteration   2: 8.401 ops/ms
# Warmup Iteration   3: 8.501 ops/ms
Iteration   1: 9.254 ops/ms
Iteration   2: 8.905 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.046 ±(99.9%) 3.359 ops/ms [Average]
  (min, avg, max) = (8.905, 9.046, 9.254), stdev = 0.184
  CI (99.9%): [5.687, 12.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.578 ops/ms
# Warmup Iteration   2: 6.840 ops/ms
# Warmup Iteration   3: 7.370 ops/ms
Iteration   1: 7.666 ops/ms
Iteration   2: 7.520 ops/ms
Iteration   3: 7.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.624 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (7.520, 7.624, 7.687), stdev = 0.091
  CI (99.9%): [5.962, 9.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.310 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.006 ms/op
Iteration   1: 3.568 ±(99.9%) 0.006 ms/op
Iteration   2: 3.672 ±(99.9%) 0.007 ms/op
Iteration   3: 3.396 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.545 ±(99.9%) 2.547 ms/op [Average]
  (min, avg, max) = (3.396, 3.545, 3.672), stdev = 0.140
  CI (99.9%): [0.998, 6.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.791 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.004 ms/op
Iteration   1: 3.395 ±(99.9%) 0.003 ms/op
Iteration   2: 3.394 ±(99.9%) 0.004 ms/op
Iteration   3: 3.383 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.391 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (3.383, 3.391, 3.395), stdev = 0.007
  CI (99.9%): [3.266, 3.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.821 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.004 ms/op
Iteration   1: 3.600 ±(99.9%) 0.004 ms/op
Iteration   2: 3.573 ±(99.9%) 0.004 ms/op
Iteration   3: 3.485 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.552 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.485, 3.552, 3.600), stdev = 0.060
  CI (99.9%): [2.456, 4.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.505 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.342 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.005 ms/op
Iteration   1: 4.235 ±(99.9%) 0.007 ms/op
Iteration   2: 3.976 ±(99.9%) 0.011 ms/op
Iteration   3: 4.168 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.126 ±(99.9%) 2.451 ms/op [Average]
  (min, avg, max) = (3.976, 4.126, 4.235), stdev = 0.134
  CI (99.9%): [1.675, 6.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.963 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.012 ms/op
Iteration   1: 3.540 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  19.623 ms/op
                 createUser·p0.9999: 22.931 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.491 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 28.274 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  21.253 ms/op
                 createUser·p0.9999: 28.672 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273190
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3950 
    [ 2.500,  5.000) = 260975 
    [ 5.000,  7.500) = 6587 
    [ 7.500, 10.000) = 1069 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.664 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.039 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.011 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  18.549 ms/op
                 existUser·p0.9999: 22.754 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.198 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  20.316 ms/op
                 existUser·p0.9999: 26.184 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.358 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  17.687 ms/op
                 existUser·p0.9999: 25.295 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284229
  mean =      3.377 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8531 
    [ 2.500,  5.000) = 268584 
    [ 5.000,  7.500) = 5977 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     25.185 ms/op
     p(99.9990) =     28.781 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.197 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
Iteration   1: 3.737 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  15.598 ms/op
                 getUser·p0.9999: 20.031 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 3.503 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   6.618 ms/op
                 getUser·p0.999:  17.708 ms/op
                 getUser·p0.9999: 20.668 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   3: 3.495 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.950 ms/op
                 getUser·p0.999:  20.799 ms/op
                 getUser·p0.9999: 24.705 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268733
  mean =      3.575 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3657 
    [ 2.500,  5.000) = 254881 
    [ 5.000,  7.500) = 7750 
    [ 7.500, 10.000) = 1579 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     23.798 ms/op
     p(99.9990) =     26.198 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.212 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.264 ±(99.9%) 0.013 ms/op
Iteration   1: 4.200 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  20.638 ms/op
                 listUser·p0.9999: 28.644 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.211 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.804 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 21.130 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.229 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227693
  mean =      4.213 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 215814 
    [ 5.000,  7.500) = 8416 
    [ 7.500, 10.000) = 2427 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 251 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     29.113 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.889 ± 3.106  ops/ms
ClientPb.existUser                       thrpt       3   9.103 ± 4.793  ops/ms
ClientPb.getUser                         thrpt       3   9.046 ± 3.359  ops/ms
ClientPb.listUser                        thrpt       3   7.624 ± 1.663  ops/ms
ClientPb.createUser                       avgt       3   3.545 ± 2.547   ms/op
ClientPb.existUser                        avgt       3   3.391 ± 0.125   ms/op
ClientPb.getUser                          avgt       3   3.552 ± 1.097   ms/op
ClientPb.listUser                         avgt       3   4.126 ± 2.451   ms/op
ClientPb.createUser                     sample  273190   3.512 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.036           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.246           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  284229   3.377 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.071           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.185           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.114           ms/op
ClientPb.getUser                        sample  268733   3.575 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.186           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.389           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.798           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  227693   4.213 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
