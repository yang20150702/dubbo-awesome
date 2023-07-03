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
# Warmup Iteration   1: 2.345 ops/ms
# Warmup Iteration   2: 5.595 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.732 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 9.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.846 ±(99.9%) 1.879 ops/ms [Average]
  (min, avg, max) = (9.732, 9.846, 9.931), stdev = 0.103
  CI (99.9%): [7.967, 11.725] (assumes normal distribution)


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
# Warmup Iteration   1: 3.067 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.998 ops/ms
Iteration   1: 10.165 ops/ms
Iteration   2: 10.205 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.198 ±(99.9%) 0.540 ops/ms [Average]
  (min, avg, max) = (10.165, 10.198, 10.223), stdev = 0.030
  CI (99.9%): [9.658, 10.738] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.458 ops/ms
# Warmup Iteration   2: 8.724 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 9.849 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.986 ±(99.9%) 2.185 ops/ms [Average]
  (min, avg, max) = (9.849, 9.986, 10.069), stdev = 0.120
  CI (99.9%): [7.801, 12.171] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.449 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 8.210 ops/ms
Iteration   1: 8.331 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 8.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.219 ±(99.9%) 3.354 ops/ms [Average]
  (min, avg, max) = (8.007, 8.219, 8.331), stdev = 0.184
  CI (99.9%): [4.865, 11.573] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.174 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.005 ms/op
Iteration   1: 3.386 ±(99.9%) 0.009 ms/op
Iteration   2: 3.270 ±(99.9%) 0.004 ms/op
Iteration   3: 3.274 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.310 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.270, 3.310, 3.386), stdev = 0.066
  CI (99.9%): [2.110, 4.510] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.143 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.007 ms/op
Iteration   1: 3.219 ±(99.9%) 0.008 ms/op
Iteration   2: 3.299 ±(99.9%) 0.006 ms/op
Iteration   3: 3.136 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.218 ±(99.9%) 1.481 ms/op [Average]
  (min, avg, max) = (3.136, 3.218, 3.299), stdev = 0.081
  CI (99.9%): [1.737, 4.699] (assumes normal distribution)


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
# Warmup Iteration   1: 8.728 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.002 ms/op
Iteration   1: 3.291 ±(99.9%) 0.005 ms/op
Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
Iteration   3: 3.323 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.287 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.249, 3.287, 3.323), stdev = 0.037
  CI (99.9%): [2.606, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 9.750 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.005 ms/op
Iteration   1: 3.850 ±(99.9%) 0.010 ms/op
Iteration   2: 3.828 ±(99.9%) 0.009 ms/op
Iteration   3: 3.824 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.834 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (3.824, 3.834, 3.850), stdev = 0.014
  CI (99.9%): [3.578, 4.090] (assumes normal distribution)


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
# Warmup Iteration   1: 8.404 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.009 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  19.039 ms/op
                 createUser·p0.9999: 21.149 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.266 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.780 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  16.777 ms/op
                 createUser·p0.9999: 21.425 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  15.045 ms/op
                 createUser·p0.9999: 20.179 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300574
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23808 
    [ 2.500,  5.000) = 269735 
    [ 5.000,  7.500) = 6109 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.342 ms/op
     p(99.9900) =     20.904 ms/op
     p(99.9990) =     22.934 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.421 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 20.998 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  15.892 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 21.027 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308062
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7780 
    [ 2.500,  5.000) = 295448 
    [ 5.000,  7.500) = 4137 
    [ 7.500, 10.000) = 293 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     12.138 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     24.067 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.989 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.010 ms/op
Iteration   1: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.725 ms/op
                 getUser·p0.999:  18.262 ms/op
                 getUser·p0.9999: 21.373 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.337 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  19.118 ms/op
                 getUser·p0.9999: 27.768 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   3: 3.364 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.556 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  14.945 ms/op
                 getUser·p0.9999: 21.709 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288274
  mean =      3.326 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16425 
    [ 2.500,  5.000) = 264129 
    [ 5.000,  7.500) = 6538 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.097 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     26.619 ms/op
     p(99.9990) =     28.001 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 10.046 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.013 ms/op
Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.944 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  16.681 ms/op
                 listUser·p0.9999: 23.327 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 3.887 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.707 ms/op
                 listUser·p0.9999: 18.425 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.941 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 16.237 ms/op
                 listUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244803
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 234642 
    [ 5.000,  7.500) = 7640 
    [ 7.500, 10.000) = 1729 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     14.552 ms/op
     p(99.9900) =     22.169 ms/op
     p(99.9990) =     23.924 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.846 ± 1.879  ops/ms
ClientPb.existUser                       thrpt       3  10.198 ± 0.540  ops/ms
ClientPb.getUser                         thrpt       3   9.986 ± 2.185  ops/ms
ClientPb.listUser                        thrpt       3   8.219 ± 3.354  ops/ms
ClientPb.createUser                       avgt       3   3.310 ± 1.200   ms/op
ClientPb.existUser                        avgt       3   3.218 ± 1.481   ms/op
ClientPb.getUser                          avgt       3   3.287 ± 0.682   ms/op
ClientPb.listUser                         avgt       3   3.834 ± 0.256   ms/op
ClientPb.createUser                     sample  300574   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.266           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.494           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.342           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.904           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.052           ms/op
ClientPb.existUser                      sample  308062   3.115 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.883           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.856           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  288274   3.326 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.097           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.975           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.619           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443           ms/op
ClientPb.listUser                       sample  244803   3.921 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.169           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
