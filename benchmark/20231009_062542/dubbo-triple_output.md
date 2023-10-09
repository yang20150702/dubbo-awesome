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
# Warmup Iteration   1: 2.211 ops/ms
# Warmup Iteration   2: 5.795 ops/ms
# Warmup Iteration   3: 8.650 ops/ms
Iteration   1: 9.328 ops/ms
Iteration   2: 9.369 ops/ms
Iteration   3: 9.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.355 ±(99.9%) 0.433 ops/ms [Average]
  (min, avg, max) = (9.328, 9.355, 9.369), stdev = 0.024
  CI (99.9%): [8.922, 9.787] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 9.093 ops/ms
# Warmup Iteration   3: 9.569 ops/ms
Iteration   1: 9.764 ops/ms
Iteration   2: 9.713 ops/ms
Iteration   3: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.798 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (9.713, 9.798, 9.917), stdev = 0.106
  CI (99.9%): [7.858, 11.739] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.629 ops/ms
# Warmup Iteration   2: 8.378 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 8.959 ops/ms
Iteration   2: 9.123 ops/ms
Iteration   3: 9.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.061 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (8.959, 9.061, 9.123), stdev = 0.090
  CI (99.9%): [7.426, 10.696] (assumes normal distribution)


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
# Warmup Iteration   1: 2.737 ops/ms
# Warmup Iteration   2: 7.212 ops/ms
# Warmup Iteration   3: 7.333 ops/ms
Iteration   1: 7.516 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.754 ±(99.9%) 3.841 ops/ms [Average]
  (min, avg, max) = (7.516, 7.754, 7.917), stdev = 0.211
  CI (99.9%): [3.913, 11.595] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.825 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.003 ms/op
Iteration   1: 3.410 ±(99.9%) 0.006 ms/op
Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
Iteration   3: 3.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.412 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.389, 3.412, 3.436), stdev = 0.024
  CI (99.9%): [2.976, 3.848] (assumes normal distribution)


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
# Warmup Iteration   1: 8.150 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.002 ms/op
Iteration   1: 3.299 ±(99.9%) 0.003 ms/op
Iteration   2: 3.317 ±(99.9%) 0.003 ms/op
Iteration   3: 3.308 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (3.299, 3.308, 3.317), stdev = 0.009
  CI (99.9%): [3.142, 3.474] (assumes normal distribution)


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
# Warmup Iteration   1: 8.677 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.003 ms/op
Iteration   1: 3.399 ±(99.9%) 0.003 ms/op
Iteration   2: 3.455 ±(99.9%) 0.002 ms/op
Iteration   3: 3.361 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.405 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.361, 3.405, 3.455), stdev = 0.047
  CI (99.9%): [2.542, 4.268] (assumes normal distribution)


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
# Warmup Iteration   1: 10.021 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.005 ms/op
Iteration   1: 4.052 ±(99.9%) 0.005 ms/op
Iteration   2: 4.075 ±(99.9%) 0.006 ms/op
Iteration   3: 4.051 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.059 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (4.051, 4.059, 4.075), stdev = 0.014
  CI (99.9%): [3.811, 4.308] (assumes normal distribution)


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
# Warmup Iteration   1: 9.333 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
Iteration   1: 3.441 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 24.239 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.578 ms/op
                 createUser·p0.999:  21.024 ms/op
                 createUser·p0.9999: 31.894 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   3: 3.490 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  17.998 ms/op
                 createUser·p0.9999: 25.057 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277908
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3540 
    [ 2.500,  5.000) = 269073 
    [ 5.000,  7.500) = 4272 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     29.433 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 9.183 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.008 ms/op
Iteration   1: 3.413 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  18.665 ms/op
                 existUser·p0.9999: 21.832 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.559 ms/op
                 existUser·p0.999:  20.545 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  10.617 ms/op
                 existUser·p0.9999: 26.104 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282336
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8034 
    [ 2.500,  5.000) = 268872 
    [ 5.000,  7.500) = 4516 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     11.971 ms/op
     p(99.9900) =     24.896 ms/op
     p(99.9990) =     27.801 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 8.504 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  19.144 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 3.418 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  21.280 ms/op
                 getUser·p0.9999: 24.368 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  18.592 ms/op
                 getUser·p0.9999: 26.834 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277837
  mean =      3.453 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2005 
    [ 2.500,  5.000) = 270006 
    [ 5.000,  7.500) = 4906 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     18.781 ms/op
     p(99.9900) =     25.271 ms/op
     p(99.9990) =     28.155 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 9.843 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.012 ms/op
Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 24.520 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   2: 4.150 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.433 ms/op
                 listUser·p0.9999: 18.098 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.107 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.953 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 19.799 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233447
  mean =      4.110 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 225679 
    [ 5.000,  7.500) = 6037 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.355 ± 0.433  ops/ms
ClientPb.existUser                       thrpt       3   9.798 ± 1.941  ops/ms
ClientPb.getUser                         thrpt       3   9.061 ± 1.635  ops/ms
ClientPb.listUser                        thrpt       3   7.754 ± 3.841  ops/ms
ClientPb.createUser                       avgt       3   3.412 ± 0.436   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 0.166   ms/op
ClientPb.getUser                          avgt       3   3.405 ± 0.863   ms/op
ClientPb.listUser                         avgt       3   4.059 ± 0.249   ms/op
ClientPb.createUser                     sample  277908   3.451 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.871           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.300           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.433           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  282336   3.398 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.500           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.971           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.896           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.901           ms/op
ClientPb.getUser                        sample  277837   3.453 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.019           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.781           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.271           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  233447   4.110 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.483           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.805           ms/op
