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
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 8.872 ops/ms
Iteration   1: 9.640 ops/ms
Iteration   2: 9.737 ops/ms
Iteration   3: 9.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.639 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (9.542, 9.639, 9.737), stdev = 0.097
  CI (99.9%): [7.862, 11.417] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 9.850 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 9.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.292 ±(99.9%) 7.388 ops/ms [Average]
  (min, avg, max) = (9.828, 10.292, 10.577), stdev = 0.405
  CI (99.9%): [2.903, 17.680] (assumes normal distribution)


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
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 8.817 ops/ms
# Warmup Iteration   3: 9.598 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 9.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.998 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (9.857, 9.998, 10.103), stdev = 0.126
  CI (99.9%): [7.692, 12.304] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.165 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 8.440 ops/ms
Iteration   1: 8.292 ops/ms
Iteration   2: 8.523 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.361 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (8.267, 8.361, 8.523), stdev = 0.141
  CI (99.9%): [5.780, 10.941] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.368 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.004 ms/op
Iteration   2: 3.278 ±(99.9%) 0.004 ms/op
Iteration   3: 3.321 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.239 ±(99.9%) 1.951 ms/op [Average]
  (min, avg, max) = (3.118, 3.239, 3.321), stdev = 0.107
  CI (99.9%): [1.288, 5.190] (assumes normal distribution)


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
# Warmup Iteration   1: 8.012 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.007 ms/op
Iteration   2: 3.215 ±(99.9%) 0.006 ms/op
Iteration   3: 3.207 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.162 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (3.064, 3.162, 3.215), stdev = 0.085
  CI (99.9%): [1.606, 4.718] (assumes normal distribution)


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
# Warmup Iteration   1: 8.611 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.346 ±(99.9%) 0.005 ms/op
Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
Iteration   3: 3.217 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.210 ±(99.9%) 2.552 ms/op [Average]
  (min, avg, max) = (3.066, 3.210, 3.346), stdev = 0.140
  CI (99.9%): [0.657, 5.762] (assumes normal distribution)


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
# Warmup Iteration   1: 9.813 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.005 ms/op
Iteration   1: 3.871 ±(99.9%) 0.003 ms/op
Iteration   2: 3.836 ±(99.9%) 0.009 ms/op
Iteration   3: 3.745 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.818 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.745, 3.818, 3.871), stdev = 0.065
  CI (99.9%): [2.631, 5.004] (assumes normal distribution)


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
# Warmup Iteration   1: 7.827 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
Iteration   1: 3.204 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  18.388 ms/op
                 createUser·p0.9999: 20.579 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  13.107 ms/op
                 createUser·p0.9999: 22.675 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.257 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.263 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  13.107 ms/op
                 createUser·p0.9999: 21.895 ms/op
                 createUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298942
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18145 
    [ 2.500,  5.000) = 274685 
    [ 5.000,  7.500) = 5208 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     15.599 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.135 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 6.631 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
Iteration   1: 3.073 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 20.335 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 27.329 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.411 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307881
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15997 
    [ 2.500,  5.000) = 286456 
    [ 5.000,  7.500) = 4604 
    [ 7.500, 10.000) = 279 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     26.254 ms/op
     p(99.9990) =     28.599 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 7.118 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.480 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
Iteration   1: 3.319 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   2: 3.362 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  17.365 ms/op
                 getUser·p0.9999: 20.676 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   5.217 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  10.636 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284341
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18075 
    [ 2.500,  5.000) = 255003 
    [ 5.000,  7.500) = 10051 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.291 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 10.416 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.598 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
Iteration   1: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 22.170 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 3.781 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.788 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.444 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251172
  mean =      3.821 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 243250 
    [ 5.000,  7.500) = 5674 
    [ 7.500, 10.000) = 1380 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     20.280 ms/op
     p(99.9990) =     22.478 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.639 ± 1.777  ops/ms
ClientPb.existUser                       thrpt       3  10.292 ± 7.388  ops/ms
ClientPb.getUser                         thrpt       3   9.998 ± 2.306  ops/ms
ClientPb.listUser                        thrpt       3   8.361 ± 2.580  ops/ms
ClientPb.createUser                       avgt       3   3.239 ± 1.951   ms/op
ClientPb.existUser                        avgt       3   3.162 ± 1.556   ms/op
ClientPb.getUser                          avgt       3   3.210 ± 2.552   ms/op
ClientPb.listUser                         avgt       3   3.818 ± 1.186   ms/op
ClientPb.createUser                     sample  298942   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.263           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.599           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.791           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.233           ms/op
ClientPb.existUser                      sample  307881   3.116 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.713           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.836           ms/op
ClientPb.getUser                        sample  284341   3.376 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.225           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.122           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.675           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.543           ms/op
ClientPb.listUser                       sample  251172   3.821 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.101           ms/op
