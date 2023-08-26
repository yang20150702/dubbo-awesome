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
# Warmup Iteration   1: 2.393 ops/ms
# Warmup Iteration   2: 6.336 ops/ms
# Warmup Iteration   3: 8.781 ops/ms
Iteration   1: 9.457 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.910 ±(99.9%) 8.897 ops/ms [Average]
  (min, avg, max) = (9.457, 9.910, 10.426), stdev = 0.488
  CI (99.9%): [1.013, 18.807] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 9.587 ops/ms
# Warmup Iteration   3: 9.904 ops/ms
Iteration   1: 10.263 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.452 ±(99.9%) 3.742 ops/ms [Average]
  (min, avg, max) = (10.263, 10.452, 10.670), stdev = 0.205
  CI (99.9%): [6.710, 14.195] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ops/ms
# Warmup Iteration   2: 8.742 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 9.808 ops/ms
Iteration   3: 9.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.824 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (9.717, 9.824, 9.948), stdev = 0.116
  CI (99.9%): [7.708, 11.940] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 7.527 ops/ms
# Warmup Iteration   3: 8.480 ops/ms
Iteration   1: 8.342 ops/ms
Iteration   2: 8.434 ops/ms
Iteration   3: 8.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.443 ±(99.9%) 1.925 ops/ms [Average]
  (min, avg, max) = (8.342, 8.443, 8.552), stdev = 0.106
  CI (99.9%): [6.518, 10.368] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.552 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.004 ms/op
Iteration   1: 3.288 ±(99.9%) 0.007 ms/op
Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
Iteration   3: 3.195 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.235 ±(99.9%) 0.877 ms/op [Average]
  (min, avg, max) = (3.195, 3.235, 3.288), stdev = 0.048
  CI (99.9%): [2.358, 4.112] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.309 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
Iteration   3: 3.116 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.041, 3.114, 3.186), stdev = 0.073
  CI (99.9%): [1.787, 4.442] (assumes normal distribution)


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
# Warmup Iteration   1: 8.519 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.002 ms/op
Iteration   1: 3.220 ±(99.9%) 0.004 ms/op
Iteration   2: 3.409 ±(99.9%) 0.005 ms/op
Iteration   3: 3.281 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.303 ±(99.9%) 1.761 ms/op [Average]
  (min, avg, max) = (3.220, 3.303, 3.409), stdev = 0.097
  CI (99.9%): [1.542, 5.064] (assumes normal distribution)


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
# Warmup Iteration   1: 9.947 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.008 ms/op
Iteration   1: 3.807 ±(99.9%) 0.005 ms/op
Iteration   2: 3.903 ±(99.9%) 0.006 ms/op
Iteration   3: 3.828 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.846 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.807, 3.846, 3.903), stdev = 0.051
  CI (99.9%): [2.921, 4.771] (assumes normal distribution)


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
# Warmup Iteration   1: 8.244 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.010 ms/op
Iteration   1: 3.301 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.290 ms/op
                 createUser·p0.9999: 20.392 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.418 ms/op
                 createUser·p0.9999: 24.085 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  13.435 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290756
  mean =      3.299 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18609 
    [ 2.500,  5.000) = 263582 
    [ 5.000,  7.500) = 7017 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     17.211 ms/op
     p(99.9900) =     22.313 ms/op
     p(99.9990) =     24.257 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 6.819 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  9.653 ms/op
                 existUser·p0.9999: 20.972 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.279 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.885 ms/op
                 existUser·p0.999:  10.104 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 3.307 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.266 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  12.774 ms/op
                 existUser·p0.9999: 23.309 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288241
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21915 
    [ 2.500,  5.000) = 258529 
    [ 5.000,  7.500) = 6732 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     23.722 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 8.218 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.010 ms/op
Iteration   1: 3.248 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 19.764 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.294 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  10.419 ms/op
                 getUser·p0.9999: 27.390 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  11.289 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294526
  mean =      3.258 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15571 
    [ 2.500,  5.000) = 267923 
    [ 5.000,  7.500) = 9168 
    [ 7.500, 10.000) = 1319 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     28.514 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 9.522 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.014 ms/op
Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.697 ms/op
                 listUser·p0.99:   7.816 ms/op
                 listUser·p0.999:  16.009 ms/op
                 listUser·p0.9999: 29.280 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  12.807 ms/op
                 listUser·p0.9999: 13.664 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.665 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250153
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 150 
    [ 2.500,  5.000) = 239694 
    [ 5.000,  7.500) = 7426 
    [ 7.500, 10.000) = 1919 
    [10.000, 12.500) = 474 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     13.727 ms/op
     p(99.9900) =     26.803 ms/op
     p(99.9990) =     29.540 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.910 ± 8.897  ops/ms
ClientPb.existUser                       thrpt       3  10.452 ± 3.742  ops/ms
ClientPb.getUser                         thrpt       3   9.824 ± 2.116  ops/ms
ClientPb.listUser                        thrpt       3   8.443 ± 1.925  ops/ms
ClientPb.createUser                       avgt       3   3.235 ± 0.877   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 1.327   ms/op
ClientPb.getUser                          avgt       3   3.303 ± 1.761   ms/op
ClientPb.listUser                         avgt       3   3.846 ± 0.925   ms/op
ClientPb.createUser                     sample  290756   3.299 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.266           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.160           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.211           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.674           ms/op
ClientPb.existUser                      sample  288241   3.330 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.945           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.233           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  294526   3.258 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.781           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.985           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  250153   3.832 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.149           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.727           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.803           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.622           ms/op
