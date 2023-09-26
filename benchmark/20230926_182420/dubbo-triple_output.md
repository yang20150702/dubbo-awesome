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
# Warmup Iteration   1: 2.292 ops/ms
# Warmup Iteration   2: 5.893 ops/ms
# Warmup Iteration   3: 9.117 ops/ms
Iteration   1: 9.673 ops/ms
Iteration   2: 9.855 ops/ms
Iteration   3: 9.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.706 ±(99.9%) 2.479 ops/ms [Average]
  (min, avg, max) = (9.589, 9.706, 9.855), stdev = 0.136
  CI (99.9%): [7.226, 12.185] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ops/ms
# Warmup Iteration   2: 8.622 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 9.875 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.964 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (9.875, 9.964, 10.015), stdev = 0.077
  CI (99.9%): [8.558, 11.369] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.278 ops/ms
# Warmup Iteration   2: 8.863 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.024 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.974 ±(99.9%) 3.326 ops/ms [Average]
  (min, avg, max) = (9.772, 9.974, 10.127), stdev = 0.182
  CI (99.9%): [6.648, 13.301] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.077 ops/ms
# Warmup Iteration   2: 7.696 ops/ms
# Warmup Iteration   3: 8.341 ops/ms
Iteration   1: 8.357 ops/ms
Iteration   2: 8.409 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.407 ±(99.9%) 0.895 ops/ms [Average]
  (min, avg, max) = (8.357, 8.407, 8.455), stdev = 0.049
  CI (99.9%): [7.512, 9.301] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.868 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.003 ms/op
Iteration   1: 3.262 ±(99.9%) 0.004 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.180 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.221 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.180, 3.221, 3.262), stdev = 0.041
  CI (99.9%): [2.477, 3.966] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.003 ms/op
Iteration   1: 3.213 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.005 ms/op
Iteration   3: 3.191 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.186 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.154, 3.186, 3.213), stdev = 0.030
  CI (99.9%): [2.639, 3.732] (assumes normal distribution)


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
# Warmup Iteration   1: 7.396 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.002 ms/op
Iteration   1: 3.213 ±(99.9%) 0.003 ms/op
Iteration   2: 3.224 ±(99.9%) 0.003 ms/op
Iteration   3: 3.208 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (3.208, 3.215, 3.224), stdev = 0.008
  CI (99.9%): [3.069, 3.361] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.522 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.005 ms/op
Iteration   1: 3.839 ±(99.9%) 0.006 ms/op
Iteration   2: 3.796 ±(99.9%) 0.006 ms/op
Iteration   3: 3.717 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.784 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (3.717, 3.784, 3.839), stdev = 0.062
  CI (99.9%): [2.657, 4.911] (assumes normal distribution)


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
# Warmup Iteration   1: 9.182 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  17.299 ms/op
                 createUser·p0.9999: 21.938 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  19.263 ms/op
                 createUser·p0.9999: 23.039 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  15.512 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292638
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12859 
    [ 2.500,  5.000) = 275252 
    [ 5.000,  7.500) = 3496 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.193 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     23.383 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 7.953 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  15.911 ms/op
                 existUser·p0.9999: 19.494 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.593 ms/op
                 existUser·p0.999:  15.615 ms/op
                 existUser·p0.9999: 19.691 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  14.147 ms/op
                 existUser·p0.9999: 21.689 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302331
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11368 
    [ 2.500,  5.000) = 286528 
    [ 5.000,  7.500) = 3472 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     15.527 ms/op
     p(99.9900) =     20.669 ms/op
     p(99.9990) =     22.410 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.623 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   6.045 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 20.787 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  19.621 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.705 ms/op
                 getUser·p0.999:  15.059 ms/op
                 getUser·p0.9999: 19.314 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294269
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9858 
    [ 2.500,  5.000) = 279550 
    [ 5.000,  7.500) = 3914 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     16.752 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.890 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 8.305 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.611 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.732 ms/op
                 listUser·p0.999:  15.406 ms/op
                 listUser·p0.9999: 21.366 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 17.894 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.760 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.153 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 14.352 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252057
  mean =      3.805 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 245860 
    [ 5.000,  7.500) = 4786 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 448 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     19.457 ms/op
     p(99.9990) =     21.641 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.706 ± 2.479  ops/ms
ClientPb.existUser                       thrpt       3   9.964 ± 1.405  ops/ms
ClientPb.getUser                         thrpt       3   9.974 ± 3.326  ops/ms
ClientPb.listUser                        thrpt       3   8.407 ± 0.895  ops/ms
ClientPb.createUser                       avgt       3   3.221 ± 0.744   ms/op
ClientPb.existUser                        avgt       3   3.186 ± 0.546   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 0.146   ms/op
ClientPb.listUser                         avgt       3   3.784 ± 1.127   ms/op
ClientPb.createUser                     sample  292638   3.279 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.021           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.193           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.658           ms/op
ClientPb.existUser                      sample  302331   3.175 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.527           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  294269   3.260 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.752           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.856           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.953           ms/op
ClientPb.listUser                       sample  252057   3.805 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.611           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.521           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.457           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.856           ms/op
