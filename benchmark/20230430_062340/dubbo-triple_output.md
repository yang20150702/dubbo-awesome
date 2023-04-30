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
# Warmup Iteration   1: 2.280 ops/ms
# Warmup Iteration   2: 5.680 ops/ms
# Warmup Iteration   3: 8.838 ops/ms
Iteration   1: 9.500 ops/ms
Iteration   2: 9.671 ops/ms
Iteration   3: 9.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.643 ±(99.9%) 2.380 ops/ms [Average]
  (min, avg, max) = (9.500, 9.643, 9.757), stdev = 0.130
  CI (99.9%): [7.263, 12.022] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.491 ops/ms
Iteration   1: 10.289 ops/ms
Iteration   2: 10.109 ops/ms
Iteration   3: 10.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.214 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (10.109, 10.214, 10.289), stdev = 0.094
  CI (99.9%): [8.503, 11.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 8.570 ops/ms
# Warmup Iteration   3: 9.365 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 9.764 ops/ms
Iteration   3: 9.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.744 ±(99.9%) 0.616 ops/ms [Average]
  (min, avg, max) = (9.705, 9.744, 9.764), stdev = 0.034
  CI (99.9%): [9.128, 10.360] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ops/ms
# Warmup Iteration   2: 7.504 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.366 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (8.301, 8.366, 8.417), stdev = 0.059
  CI (99.9%): [7.284, 9.448] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.919 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.005 ms/op
Iteration   1: 3.189 ±(99.9%) 0.003 ms/op
Iteration   2: 3.321 ±(99.9%) 0.011 ms/op
Iteration   3: 3.179 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.230 ±(99.9%) 1.454 ms/op [Average]
  (min, avg, max) = (3.179, 3.230, 3.321), stdev = 0.080
  CI (99.9%): [1.776, 4.683] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.741 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.004 ms/op
Iteration   1: 3.125 ±(99.9%) 0.005 ms/op
Iteration   2: 3.278 ±(99.9%) 0.004 ms/op
Iteration   3: 3.150 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.184 ±(99.9%) 1.500 ms/op [Average]
  (min, avg, max) = (3.125, 3.184, 3.278), stdev = 0.082
  CI (99.9%): [1.684, 4.684] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.115 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.003 ms/op
Iteration   1: 3.306 ±(99.9%) 0.007 ms/op
Iteration   2: 3.201 ±(99.9%) 0.004 ms/op
Iteration   3: 3.195 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.195, 3.234, 3.306), stdev = 0.062
  CI (99.9%): [2.100, 4.368] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.664 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.005 ms/op
Iteration   1: 3.846 ±(99.9%) 0.008 ms/op
Iteration   2: 3.705 ±(99.9%) 0.013 ms/op
Iteration   3: 3.778 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.776 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (3.705, 3.776, 3.846), stdev = 0.070
  CI (99.9%): [2.494, 5.058] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.570 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.011 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.659 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 23.435 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.289 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  16.863 ms/op
                 createUser·p0.9999: 24.925 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  11.216 ms/op
                 createUser·p0.9999: 23.171 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294134
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12497 
    [ 2.500,  5.000) = 276905 
    [ 5.000,  7.500) = 3802 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.464 ms/op
     p(99.9900) =     23.762 ms/op
     p(99.9990) =     26.349 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.860 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 27.001 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 21.978 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 21.070 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302428
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17754 
    [ 2.500,  5.000) = 279126 
    [ 5.000,  7.500) = 4884 
    [ 7.500, 10.000) = 311 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 168 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     26.011 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 7.978 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.011 ms/op
Iteration   1: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 21.400 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.359 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  20.742 ms/op
                 getUser·p0.9999: 24.330 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.833 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  11.682 ms/op
                 getUser·p0.9999: 22.062 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291545
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10183 
    [ 2.500,  5.000) = 275509 
    [ 5.000,  7.500) = 4918 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     14.367 ms/op
     p(99.9900) =     23.217 ms/op
     p(99.9990) =     24.890 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 10.014 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.013 ms/op
Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 21.636 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 3.840 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.150 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 20.404 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.817 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 18.043 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250504
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 242754 
    [ 5.000,  7.500) = 5580 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     22.069 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.643 ± 2.380  ops/ms
ClientPb.existUser                       thrpt       3  10.214 ± 1.711  ops/ms
ClientPb.getUser                         thrpt       3   9.744 ± 0.616  ops/ms
ClientPb.listUser                        thrpt       3   8.366 ± 1.082  ops/ms
ClientPb.createUser                       avgt       3   3.230 ± 1.454   ms/op
ClientPb.existUser                        avgt       3   3.184 ± 1.500   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 1.134   ms/op
ClientPb.listUser                         avgt       3   3.776 ± 1.282   ms/op
ClientPb.createUser                     sample  294134   3.261 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.016           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.762           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.411           ms/op
ClientPb.existUser                      sample  302428   3.172 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.682           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.011           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279           ms/op
ClientPb.getUser                        sample  291545   3.292 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.217           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.738           ms/op
ClientPb.listUser                       sample  250504   3.828 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364           ms/op
