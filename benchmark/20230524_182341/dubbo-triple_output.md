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
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 5.835 ops/ms
# Warmup Iteration   3: 9.502 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 9.899 ops/ms
Iteration   3: 9.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.893 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (9.788, 9.893, 9.992), stdev = 0.102
  CI (99.9%): [8.034, 11.752] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 9.314 ops/ms
# Warmup Iteration   3: 10.128 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 10.523 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.286 ±(99.9%) 8.298 ops/ms [Average]
  (min, avg, max) = (9.762, 10.286, 10.573), stdev = 0.455
  CI (99.9%): [1.989, 18.584] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 9.515 ops/ms
# Warmup Iteration   3: 9.836 ops/ms
Iteration   1: 10.175 ops/ms
Iteration   2: 9.735 ops/ms
Iteration   3: 10.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.042 ±(99.9%) 4.868 ops/ms [Average]
  (min, avg, max) = (9.735, 10.042, 10.216), stdev = 0.267
  CI (99.9%): [5.174, 14.910] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.252 ops/ms
# Warmup Iteration   2: 7.868 ops/ms
# Warmup Iteration   3: 8.341 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.515 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.530 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (8.425, 8.530, 8.651), stdev = 0.114
  CI (99.9%): [6.456, 10.605] (assumes normal distribution)


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
# Warmup Iteration   1: 8.922 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.004 ms/op
Iteration   2: 3.138 ±(99.9%) 0.006 ms/op
Iteration   3: 3.250 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.208 ±(99.9%) 1.118 ms/op [Average]
  (min, avg, max) = (3.138, 3.208, 3.250), stdev = 0.061
  CI (99.9%): [2.090, 4.326] (assumes normal distribution)


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
# Warmup Iteration   1: 6.781 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.005 ms/op
Iteration   1: 3.100 ±(99.9%) 0.005 ms/op
Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
Iteration   3: 3.148 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.110 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.081, 3.110, 3.148), stdev = 0.035
  CI (99.9%): [2.477, 3.743] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.340 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.005 ms/op
Iteration   1: 3.171 ±(99.9%) 0.003 ms/op
Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
Iteration   3: 3.115 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.121 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (3.078, 3.121, 3.171), stdev = 0.047
  CI (99.9%): [2.271, 3.972] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.379 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.009 ms/op
Iteration   1: 3.581 ±(99.9%) 0.010 ms/op
Iteration   2: 3.770 ±(99.9%) 0.006 ms/op
Iteration   3: 3.824 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.725 ±(99.9%) 2.327 ms/op [Average]
  (min, avg, max) = (3.581, 3.725, 3.824), stdev = 0.128
  CI (99.9%): [1.398, 6.052] (assumes normal distribution)


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
# Warmup Iteration   1: 7.677 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  17.499 ms/op
                 createUser·p0.9999: 21.385 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  10.000 ms/op
                 createUser·p0.9999: 23.987 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301127
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27449 
    [ 2.500,  5.000) = 268076 
    [ 5.000,  7.500) = 4890 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     15.208 ms/op
     p(99.9900) =     22.580 ms/op
     p(99.9990) =     24.477 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.593 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
Iteration   1: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  10.775 ms/op
                 existUser·p0.9999: 18.840 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  13.638 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  14.480 ms/op
                 existUser·p0.9999: 20.326 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312139
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32867 
    [ 2.500,  5.000) = 274583 
    [ 5.000,  7.500) = 3922 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.224 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     21.684 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 7.733 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
Iteration   1: 3.284 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  14.735 ms/op
                 getUser·p0.9999: 18.039 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 21.300 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  10.641 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297199
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11968 
    [ 2.500,  5.000) = 277646 
    [ 5.000,  7.500) = 6694 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     21.425 ms/op
     p(99.9990) =     26.117 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 8.105 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.011 ms/op
Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  16.708 ms/op
                 listUser·p0.9999: 22.042 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 3.873 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.566 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 14.798 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   3: 3.764 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.313 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 14.549 ms/op
                 listUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250877
  mean =      3.827 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 241559 
    [ 5.000,  7.500) = 7091 
    [ 7.500, 10.000) = 1428 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     20.543 ms/op
     p(99.9990) =     22.609 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.893 ± 1.859  ops/ms
ClientPb.existUser                       thrpt       3  10.286 ± 8.298  ops/ms
ClientPb.getUser                         thrpt       3  10.042 ± 4.868  ops/ms
ClientPb.listUser                        thrpt       3   8.530 ± 2.075  ops/ms
ClientPb.createUser                       avgt       3   3.208 ± 1.118   ms/op
ClientPb.existUser                        avgt       3   3.110 ± 0.633   ms/op
ClientPb.getUser                          avgt       3   3.121 ± 0.851   ms/op
ClientPb.listUser                         avgt       3   3.725 ± 2.327   ms/op
ClientPb.createUser                     sample  301127   3.187 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.787           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.580           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.936           ms/op
ClientPb.existUser                      sample  312139   3.073 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.218           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.118           ms/op
ClientPb.getUser                        sample  297199   3.228 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.222           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.425           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182           ms/op
ClientPb.listUser                       sample  250877   3.827 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.543           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.741           ms/op
