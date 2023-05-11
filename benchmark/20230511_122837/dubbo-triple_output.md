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
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 5.998 ops/ms
# Warmup Iteration   3: 9.142 ops/ms
Iteration   1: 9.630 ops/ms
Iteration   2: 9.627 ops/ms
Iteration   3: 10.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.774 ±(99.9%) 4.611 ops/ms [Average]
  (min, avg, max) = (9.627, 9.774, 10.066), stdev = 0.253
  CI (99.9%): [5.163, 14.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ops/ms
# Warmup Iteration   2: 9.795 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.391 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 10.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.470 ±(99.9%) 4.534 ops/ms [Average]
  (min, avg, max) = (10.271, 10.470, 10.749), stdev = 0.249
  CI (99.9%): [5.936, 15.005] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.495 ops/ms
# Warmup Iteration   2: 8.964 ops/ms
# Warmup Iteration   3: 10.055 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.345 ops/ms
Iteration   3: 10.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.195 ±(99.9%) 2.915 ops/ms [Average]
  (min, avg, max) = (10.027, 10.195, 10.345), stdev = 0.160
  CI (99.9%): [7.279, 13.110] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 7.797 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.530 ops/ms
Iteration   2: 8.651 ops/ms
Iteration   3: 8.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.594 ±(99.9%) 1.101 ops/ms [Average]
  (min, avg, max) = (8.530, 8.594, 8.651), stdev = 0.060
  CI (99.9%): [7.493, 9.695] (assumes normal distribution)


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
# Warmup Iteration   1: 7.991 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.010 ms/op
Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
Iteration   3: 3.125 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.146 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.111, 3.146, 3.200), stdev = 0.048
  CI (99.9%): [2.276, 4.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.269 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.004 ms/op
Iteration   1: 3.090 ±(99.9%) 0.003 ms/op
Iteration   2: 3.190 ±(99.9%) 0.005 ms/op
Iteration   3: 2.999 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.093 ±(99.9%) 1.747 ms/op [Average]
  (min, avg, max) = (2.999, 3.093, 3.190), stdev = 0.096
  CI (99.9%): [1.346, 4.840] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.378 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.002 ms/op
Iteration   1: 3.182 ±(99.9%) 0.007 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 3.128 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.133 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (3.089, 3.133, 3.182), stdev = 0.047
  CI (99.9%): [2.273, 3.993] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.005 ms/op
Iteration   1: 3.907 ±(99.9%) 0.004 ms/op
Iteration   2: 3.831 ±(99.9%) 0.009 ms/op
Iteration   3: 3.728 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.822 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (3.728, 3.822, 3.907), stdev = 0.090
  CI (99.9%): [2.187, 5.457] (assumes normal distribution)


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
# Warmup Iteration   1: 7.993 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 20.908 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  8.757 ms/op
                 createUser·p0.9999: 23.385 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.254 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  13.812 ms/op
                 createUser·p0.9999: 16.722 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298986
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20840 
    [ 2.500,  5.000) = 271583 
    [ 5.000,  7.500) = 5602 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 7.081 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.009 ms/op
Iteration   1: 3.063 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  8.364 ms/op
                 existUser·p0.9999: 22.698 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  14.399 ms/op
                 existUser·p0.9999: 20.897 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310193
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21746 
    [ 2.500,  5.000) = 283916 
    [ 5.000,  7.500) = 3872 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     13.294 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     23.128 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 7.348 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.011 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.840 ms/op
                 getUser·p0.999:  9.480 ms/op
                 getUser·p0.9999: 20.228 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  12.617 ms/op
                 getUser·p0.9999: 23.993 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.176 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  13.428 ms/op
                 getUser·p0.9999: 22.749 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293769
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16805 
    [ 2.500,  5.000) = 267508 
    [ 5.000,  7.500) = 8558 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.480 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 8.273 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.011 ms/op
Iteration   1: 3.780 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.887 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 21.186 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.211 ms/op
                 listUser·p0.9999: 17.846 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 3.684 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255991
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 246212 
    [ 5.000,  7.500) = 7589 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     19.248 ms/op
     p(99.9990) =     22.002 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.774 ± 4.611  ops/ms
ClientPb.existUser                       thrpt       3  10.470 ± 4.534  ops/ms
ClientPb.getUser                         thrpt       3  10.195 ± 2.915  ops/ms
ClientPb.listUser                        thrpt       3   8.594 ± 1.101  ops/ms
ClientPb.createUser                       avgt       3   3.146 ± 0.869   ms/op
ClientPb.existUser                        avgt       3   3.093 ± 1.747   ms/op
ClientPb.getUser                          avgt       3   3.133 ± 0.860   ms/op
ClientPb.listUser                         avgt       3   3.822 ± 1.635   ms/op
ClientPb.createUser                     sample  298986   3.208 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.254           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.592           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.746           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.888           ms/op
ClientPb.existUser                      sample  310193   3.095 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.724           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.294           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.118           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.495           ms/op
ClientPb.getUser                        sample  293769   3.268 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.013           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.386           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.364           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.674           ms/op
ClientPb.listUser                       sample  255991   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.436           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.592           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.248           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.053           ms/op
