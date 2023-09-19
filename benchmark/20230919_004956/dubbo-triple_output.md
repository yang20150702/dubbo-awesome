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
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.607 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 9.051 ops/ms
Iteration   2: 9.392 ops/ms
Iteration   3: 9.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.269 ±(99.9%) 3.453 ops/ms [Average]
  (min, avg, max) = (9.051, 9.269, 9.392), stdev = 0.189
  CI (99.9%): [5.816, 12.722] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.947 ops/ms
# Warmup Iteration   2: 9.003 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.606 ops/ms
Iteration   2: 9.630 ops/ms
Iteration   3: 9.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.624 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (9.606, 9.624, 9.637), stdev = 0.016
  CI (99.9%): [9.328, 9.920] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 8.085 ops/ms
# Warmup Iteration   3: 8.787 ops/ms
Iteration   1: 9.181 ops/ms
Iteration   2: 9.322 ops/ms
Iteration   3: 9.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.246 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (9.181, 9.246, 9.322), stdev = 0.071
  CI (99.9%): [7.953, 10.540] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.999 ops/ms
# Warmup Iteration   2: 7.324 ops/ms
# Warmup Iteration   3: 7.646 ops/ms
Iteration   1: 7.790 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 7.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.833 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (7.790, 7.833, 7.902), stdev = 0.061
  CI (99.9%): [6.728, 8.938] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.909 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.006 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
Iteration   2: 3.474 ±(99.9%) 0.005 ms/op
Iteration   3: 3.479 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.477 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (3.474, 3.477, 3.479), stdev = 0.003
  CI (99.9%): [3.425, 3.529] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.254 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.002 ms/op
Iteration   1: 3.263 ±(99.9%) 0.004 ms/op
Iteration   2: 3.280 ±(99.9%) 0.002 ms/op
Iteration   3: 3.349 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.297 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.263, 3.297, 3.349), stdev = 0.046
  CI (99.9%): [2.465, 4.130] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.848 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.005 ms/op
Iteration   1: 3.490 ±(99.9%) 0.004 ms/op
Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
Iteration   3: 3.432 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.432, 3.465, 3.490), stdev = 0.030
  CI (99.9%): [2.919, 4.010] (assumes normal distribution)


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
# Warmup Iteration   1: 10.591 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.008 ms/op
Iteration   1: 4.082 ±(99.9%) 0.006 ms/op
Iteration   2: 4.085 ±(99.9%) 0.006 ms/op
Iteration   3: 4.041 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.069 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (4.041, 4.069, 4.085), stdev = 0.025
  CI (99.9%): [3.619, 4.519] (assumes normal distribution)


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
# Warmup Iteration   1: 10.324 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.012 ms/op
Iteration   1: 3.427 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  21.318 ms/op
                 createUser·p0.9999: 25.811 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  24.397 ms/op
                 createUser·p0.9999: 26.987 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.554 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  18.449 ms/op
                 createUser·p0.9999: 27.034 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277426
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8836 
    [ 2.500,  5.000) = 263107 
    [ 5.000,  7.500) = 4355 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 125 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     26.788 ms/op
     p(99.9990) =     27.664 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 8.685 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.008 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  11.754 ms/op
                 existUser·p0.9999: 23.928 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  24.445 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 3.390 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  12.659 ms/op
                 existUser·p0.9999: 29.037 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283184
  mean =      3.387 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8834 
    [ 2.500,  5.000) = 268674 
    [ 5.000,  7.500) = 4363 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.489 ms/op
     p(99.9000) =     13.199 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     30.136 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 8.796 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.010 ms/op
Iteration   1: 3.556 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.827 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.430 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  19.160 ms/op
                 getUser·p0.9999: 21.944 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.395 ms/op
                 getUser·p0.999:  19.418 ms/op
                 getUser·p0.9999: 26.303 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274658
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3088 
    [ 2.500,  5.000) = 264891 
    [ 5.000,  7.500) = 5403 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     17.673 ms/op
     p(99.9900) =     24.430 ms/op
     p(99.9990) =     27.010 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 11.250 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.014 ms/op
Iteration   1: 4.201 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  21.194 ms/op
                 listUser·p0.9999: 26.129 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   2: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.044 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233518
  mean =      4.110 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 223733 
    [ 5.000,  7.500) = 7769 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     26.466 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.269 ± 3.453  ops/ms
ClientPb.existUser                       thrpt       3   9.624 ± 0.296  ops/ms
ClientPb.getUser                         thrpt       3   9.246 ± 1.293  ops/ms
ClientPb.listUser                        thrpt       3   7.833 ± 1.105  ops/ms
ClientPb.createUser                       avgt       3   3.477 ± 0.052   ms/op
ClientPb.existUser                        avgt       3   3.297 ± 0.833   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 0.546   ms/op
ClientPb.listUser                         avgt       3   4.069 ± 0.450   ms/op
ClientPb.createUser                     sample  277426   3.457 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.102           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.788           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.722           ms/op
ClientPb.existUser                      sample  283184   3.387 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.199           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.623           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  274658   3.496 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.208           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.673           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.430           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  233518   4.110 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.674           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.542           ms/op
