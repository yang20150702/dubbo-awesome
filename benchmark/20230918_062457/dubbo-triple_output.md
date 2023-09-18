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
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.329 ops/ms
# Warmup Iteration   3: 9.332 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 9.779 ops/ms
Iteration   3: 9.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.663 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (9.512, 9.663, 9.779), stdev = 0.137
  CI (99.9%): [7.165, 12.161] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 10.128 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.969 ±(99.9%) 3.215 ops/ms [Average]
  (min, avg, max) = (9.865, 9.969, 10.173), stdev = 0.176
  CI (99.9%): [6.755, 13.184] (assumes normal distribution)


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
# Warmup Iteration   1: 3.391 ops/ms
# Warmup Iteration   2: 8.943 ops/ms
# Warmup Iteration   3: 9.589 ops/ms
Iteration   1: 9.847 ops/ms
Iteration   2: 9.748 ops/ms
Iteration   3: 9.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.773 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (9.723, 9.773, 9.847), stdev = 0.066
  CI (99.9%): [8.571, 10.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.072 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 8.328 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.197 ops/ms
Iteration   3: 8.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.247 ±(99.9%) 2.220 ops/ms [Average]
  (min, avg, max) = (8.159, 8.247, 8.386), stdev = 0.122
  CI (99.9%): [6.027, 10.467] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.969 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.006 ms/op
Iteration   1: 3.457 ±(99.9%) 0.002 ms/op
Iteration   2: 3.239 ±(99.9%) 0.009 ms/op
Iteration   3: 3.524 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.406 ±(99.9%) 2.721 ms/op [Average]
  (min, avg, max) = (3.239, 3.406, 3.524), stdev = 0.149
  CI (99.9%): [0.685, 6.128] (assumes normal distribution)


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
# Warmup Iteration   1: 8.072 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.002 ms/op
Iteration   1: 3.232 ±(99.9%) 0.005 ms/op
Iteration   2: 3.169 ±(99.9%) 0.006 ms/op
Iteration   3: 3.143 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.181 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.143, 3.181, 3.232), stdev = 0.045
  CI (99.9%): [2.352, 4.010] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.578 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.004 ms/op
Iteration   1: 3.183 ±(99.9%) 0.002 ms/op
Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
Iteration   3: 3.224 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.183, 3.216, 3.242), stdev = 0.030
  CI (99.9%): [2.662, 3.770] (assumes normal distribution)


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
# Warmup Iteration   1: 8.046 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.006 ms/op
Iteration   1: 3.877 ±(99.9%) 0.004 ms/op
Iteration   2: 3.863 ±(99.9%) 0.007 ms/op
Iteration   3: 3.797 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.846 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (3.797, 3.846, 3.877), stdev = 0.043
  CI (99.9%): [3.062, 4.630] (assumes normal distribution)


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
# Warmup Iteration   1: 8.999 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.007 ms/op
Iteration   1: 3.307 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  16.763 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.326 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.250 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  10.331 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292401
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11832 
    [ 2.500,  5.000) = 276136 
    [ 5.000,  7.500) = 3640 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     14.208 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     24.059 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.028 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.008 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  15.088 ms/op
                 existUser·p0.9999: 20.347 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  9.520 ms/op
                 existUser·p0.9999: 22.932 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  14.025 ms/op
                 existUser·p0.9999: 22.381 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300464
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15896 
    [ 2.500,  5.000) = 279830 
    [ 5.000,  7.500) = 4027 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     12.987 ms/op
     p(99.9900) =     22.477 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.820 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.010 ms/op
Iteration   1: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  17.610 ms/op
                 getUser·p0.9999: 20.437 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  17.188 ms/op
                 getUser·p0.9999: 22.694 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  15.859 ms/op
                 getUser·p0.9999: 23.893 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294513
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10951 
    [ 2.500,  5.000) = 278475 
    [ 5.000,  7.500) = 4231 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     16.088 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.023 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 8.046 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
Iteration   1: 3.882 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 20.996 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 3.865 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.720 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.885 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.954 ms/op
                 listUser·p0.9999: 20.261 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247463
  mean =      3.877 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 240692 
    [ 5.000,  7.500) = 5346 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 376 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     19.711 ms/op
     p(99.9990) =     21.401 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.663 ± 2.498  ops/ms
ClientPb.existUser                       thrpt       3   9.969 ± 3.215  ops/ms
ClientPb.getUser                         thrpt       3   9.773 ± 1.202  ops/ms
ClientPb.listUser                        thrpt       3   8.247 ± 2.220  ops/ms
ClientPb.createUser                       avgt       3   3.406 ± 2.721   ms/op
ClientPb.existUser                        avgt       3   3.181 ± 0.829   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 0.554   ms/op
ClientPb.listUser                         avgt       3   3.846 ± 0.784   ms/op
ClientPb.createUser                     sample  292401   3.281 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.902           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.086           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  300464   3.192 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.135           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.987           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.477           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.052           ms/op
ClientPb.getUser                        sample  294513   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.041           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.088           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.379           ms/op
ClientPb.listUser                       sample  247463   3.877 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.781           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.711           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.496           ms/op
