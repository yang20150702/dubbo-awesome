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
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 5.409 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 9.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.881 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (9.781, 9.881, 10.024), stdev = 0.127
  CI (99.9%): [7.567, 12.196] (assumes normal distribution)


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
# Warmup Iteration   1: 3.516 ops/ms
# Warmup Iteration   2: 8.663 ops/ms
# Warmup Iteration   3: 9.980 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 9.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.074 ±(99.9%) 4.343 ops/ms [Average]
  (min, avg, max) = (9.842, 10.074, 10.317), stdev = 0.238
  CI (99.9%): [5.731, 14.417] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 8.600 ops/ms
# Warmup Iteration   3: 9.442 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 9.528 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.563 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (9.486, 9.563, 9.675), stdev = 0.100
  CI (99.9%): [7.748, 11.379] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 7.519 ops/ms
# Warmup Iteration   3: 8.283 ops/ms
Iteration   1: 8.251 ops/ms
Iteration   2: 8.129 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.204 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (8.129, 8.204, 8.251), stdev = 0.066
  CI (99.9%): [7.007, 9.400] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.832 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.004 ms/op
Iteration   1: 3.367 ±(99.9%) 0.008 ms/op
Iteration   2: 3.287 ±(99.9%) 0.005 ms/op
Iteration   3: 3.273 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.309 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.273, 3.309, 3.367), stdev = 0.051
  CI (99.9%): [2.384, 4.234] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.475 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.228 ±(99.9%) 0.003 ms/op
Iteration   3: 3.302 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.213 ±(99.9%) 1.777 ms/op [Average]
  (min, avg, max) = (3.109, 3.213, 3.302), stdev = 0.097
  CI (99.9%): [1.436, 4.990] (assumes normal distribution)


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
# Warmup Iteration   1: 8.265 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.003 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
Iteration   3: 3.314 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.263 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (3.167, 3.263, 3.314), stdev = 0.083
  CI (99.9%): [1.754, 4.772] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.371 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.827 ±(99.9%) 0.012 ms/op
Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
Iteration   3: 3.688 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (3.688, 3.757, 3.827), stdev = 0.070
  CI (99.9%): [2.489, 5.025] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.687 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.008 ms/op
Iteration   1: 3.304 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 30.113 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 3.279 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.663 ms/op
                 createUser·p0.999:  21.692 ms/op
                 createUser·p0.9999: 26.527 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  19.268 ms/op
                 createUser·p0.9999: 25.815 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290163
  mean =      3.305 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13533 
    [ 2.500,  5.000) = 270854 
    [ 5.000,  7.500) = 4565 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     20.109 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.986 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.009 ms/op
Iteration   1: 3.084 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 24.269 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  11.292 ms/op
                 existUser·p0.9999: 23.359 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 26.175 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307944
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16699 
    [ 2.500,  5.000) = 286659 
    [ 5.000,  7.500) = 3694 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     10.776 ms/op
     p(99.9900) =     24.629 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.071 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.450 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 30.310 ms/op
                 getUser·p1.00:   32.965 ms/op

Iteration   2: 3.240 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  11.785 ms/op
                 getUser·p0.9999: 21.729 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  15.801 ms/op
                 getUser·p0.9999: 23.085 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290233
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14197 
    [ 2.500,  5.000) = 268097 
    [ 5.000,  7.500) = 6876 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     16.933 ms/op
     p(99.9900) =     28.376 ms/op
     p(99.9990) =     32.965 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.486 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.012 ms/op
Iteration   1: 3.849 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  16.135 ms/op
                 listUser·p0.9999: 20.830 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.828 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 20.173 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 3.819 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250557
  mean =      3.832 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 243469 
    [ 5.000,  7.500) = 5221 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     21.839 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.881 ± 2.315  ops/ms
ClientPb.existUser                       thrpt       3  10.074 ± 4.343  ops/ms
ClientPb.getUser                         thrpt       3   9.563 ± 1.815  ops/ms
ClientPb.listUser                        thrpt       3   8.204 ± 1.197  ops/ms
ClientPb.createUser                       avgt       3   3.309 ± 0.925   ms/op
ClientPb.existUser                        avgt       3   3.213 ± 1.777   ms/op
ClientPb.getUser                          avgt       3   3.263 ± 1.509   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 1.268   ms/op
ClientPb.createUser                     sample  290163   3.305 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.067           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.109           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.739           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  307944   3.118 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.776           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.629           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  290233   3.305 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.941           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.933           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.376           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  250557   3.832 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.364           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.369           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.218           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.987           ms/op
