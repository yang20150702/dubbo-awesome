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
# Warmup Iteration   1: 2.709 ops/ms
# Warmup Iteration   2: 6.398 ops/ms
# Warmup Iteration   3: 8.816 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 10.089 ops/ms
Iteration   3: 9.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.863 ±(99.9%) 3.663 ops/ms [Average]
  (min, avg, max) = (9.705, 9.863, 10.089), stdev = 0.201
  CI (99.9%): [6.201, 13.526] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 9.282 ops/ms
# Warmup Iteration   3: 9.754 ops/ms
Iteration   1: 10.076 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.168 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (10.076, 10.168, 10.229), stdev = 0.081
  CI (99.9%): [8.692, 11.645] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ops/ms
# Warmup Iteration   2: 9.307 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 9.821 ops/ms
Iteration   3: 10.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.904 ±(99.9%) 2.178 ops/ms [Average]
  (min, avg, max) = (9.821, 9.904, 10.041), stdev = 0.119
  CI (99.9%): [7.726, 12.082] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.516 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 8.425 ops/ms
Iteration   1: 8.260 ops/ms
Iteration   2: 8.189 ops/ms
Iteration   3: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.302 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (8.189, 8.302, 8.456), stdev = 0.138
  CI (99.9%): [5.786, 10.818] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.106 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.002 ms/op
Iteration   1: 3.191 ±(99.9%) 0.003 ms/op
Iteration   2: 3.149 ±(99.9%) 0.010 ms/op
Iteration   3: 3.250 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.196 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.149, 3.196, 3.250), stdev = 0.051
  CI (99.9%): [2.271, 4.122] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.245 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.005 ms/op
Iteration   1: 3.272 ±(99.9%) 0.005 ms/op
Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
Iteration   3: 3.072 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.158 ±(99.9%) 1.875 ms/op [Average]
  (min, avg, max) = (3.072, 3.158, 3.272), stdev = 0.103
  CI (99.9%): [1.283, 5.033] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.848 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.004 ms/op
Iteration   1: 3.173 ±(99.9%) 0.003 ms/op
Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
Iteration   3: 3.219 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.210 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.173, 3.210, 3.238), stdev = 0.034
  CI (99.9%): [2.592, 3.828] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 8.736 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.004 ms/op
Iteration   1: 3.845 ±(99.9%) 0.004 ms/op
Iteration   2: 3.800 ±(99.9%) 0.004 ms/op
Iteration   3: 3.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.823 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.800, 3.823, 3.845), stdev = 0.022
  CI (99.9%): [3.414, 4.232] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 20.777 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 23.000 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.273 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  16.174 ms/op
                 createUser·p0.9999: 20.508 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297163
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11834 
    [ 2.500,  5.000) = 279388 
    [ 5.000,  7.500) = 4666 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.445 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
Iteration   1: 3.183 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  9.575 ms/op
                 existUser·p0.9999: 24.566 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   2: 3.103 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  10.176 ms/op
                 existUser·p0.9999: 22.141 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 3.231 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  16.436 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302366
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13607 
    [ 2.500,  5.000) = 281596 
    [ 5.000,  7.500) = 5786 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.016 ms/op
     p(99.9000) =     16.094 ms/op
     p(99.9900) =     23.013 ms/op
     p(99.9990) =     25.096 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 7.420 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.010 ms/op
Iteration   1: 3.194 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  19.359 ms/op
                 getUser·p0.9999: 22.337 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  11.927 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.257 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  14.056 ms/op
                 getUser·p0.9999: 23.195 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296381
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11300 
    [ 2.500,  5.000) = 275598 
    [ 5.000,  7.500) = 8012 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     24.809 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 9.007 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.013 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.220 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  14.310 ms/op
                 listUser·p0.9999: 19.653 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.372 ms/op
                 listUser·p0.9999: 21.755 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  13.618 ms/op
                 listUser·p0.9999: 14.533 ms/op
                 listUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248370
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 237220 
    [ 5.000,  7.500) = 8147 
    [ 7.500, 10.000) = 2132 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.862 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     13.937 ms/op
     p(99.9900) =     19.178 ms/op
     p(99.9990) =     22.251 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.863 ± 3.663  ops/ms
ClientPb.existUser                       thrpt       3  10.168 ± 1.477  ops/ms
ClientPb.getUser                         thrpt       3   9.904 ± 2.178  ops/ms
ClientPb.listUser                        thrpt       3   8.302 ± 2.516  ops/ms
ClientPb.createUser                       avgt       3   3.196 ± 0.925   ms/op
ClientPb.existUser                        avgt       3   3.158 ± 1.875   ms/op
ClientPb.getUser                          avgt       3   3.210 ± 0.618   ms/op
ClientPb.listUser                         avgt       3   3.823 ± 0.409   ms/op
ClientPb.createUser                     sample  297163   3.232 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.660           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.105           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.282           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  302366   3.172 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.975           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.016           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.094           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166           ms/op
ClientPb.getUser                        sample  296381   3.238 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.096           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.383           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.855           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.904           ms/op
ClientPb.listUser                       sample  248370   3.861 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.937           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.178           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
