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
# Warmup Iteration   1: 2.393 ops/ms
# Warmup Iteration   2: 6.128 ops/ms
# Warmup Iteration   3: 9.078 ops/ms
Iteration   1: 9.566 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.453 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (9.252, 9.453, 9.566), stdev = 0.174
  CI (99.9%): [6.278, 12.628] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.621 ops/ms
# Warmup Iteration   3: 9.676 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 9.672 ops/ms
Iteration   3: 9.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.675 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (9.594, 9.675, 9.760), stdev = 0.083
  CI (99.9%): [8.158, 11.193] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.023 ops/ms
# Warmup Iteration   2: 7.481 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.637 ops/ms
Iteration   2: 9.688 ops/ms
Iteration   3: 9.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.583 ±(99.9%) 2.543 ops/ms [Average]
  (min, avg, max) = (9.425, 9.583, 9.688), stdev = 0.139
  CI (99.9%): [7.040, 12.127] (assumes normal distribution)


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
# Warmup Iteration   1: 2.792 ops/ms
# Warmup Iteration   2: 7.144 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.050 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (7.960, 8.050, 8.104), stdev = 0.079
  CI (99.9%): [6.616, 9.484] (assumes normal distribution)


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
# Warmup Iteration   1: 10.869 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.003 ms/op
Iteration   1: 3.529 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.007 ms/op
Iteration   3: 3.428 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.428, 3.474, 3.529), stdev = 0.051
  CI (99.9%): [2.538, 4.410] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.007 ms/op
Iteration   1: 3.186 ±(99.9%) 0.006 ms/op
Iteration   2: 3.331 ±(99.9%) 0.005 ms/op
Iteration   3: 3.249 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.255 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (3.186, 3.255, 3.331), stdev = 0.073
  CI (99.9%): [1.931, 4.579] (assumes normal distribution)


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
# Warmup Iteration   1: 8.194 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.007 ms/op
Iteration   1: 3.439 ±(99.9%) 0.006 ms/op
Iteration   2: 3.548 ±(99.9%) 0.005 ms/op
Iteration   3: 3.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.505 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (3.439, 3.505, 3.548), stdev = 0.058
  CI (99.9%): [2.440, 4.570] (assumes normal distribution)


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
# Warmup Iteration   1: 11.171 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.010 ms/op
Iteration   1: 3.846 ±(99.9%) 0.013 ms/op
Iteration   2: 3.899 ±(99.9%) 0.012 ms/op
Iteration   3: 3.990 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.912 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.846, 3.912, 3.990), stdev = 0.073
  CI (99.9%): [2.585, 5.238] (assumes normal distribution)


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
# Warmup Iteration   1: 8.969 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.011 ms/op
Iteration   1: 3.317 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  16.665 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.427 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  21.713 ms/op
                 createUser·p0.9999: 29.293 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   3: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 22.702 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280676
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4978 
    [ 2.500,  5.000) = 270081 
    [ 5.000,  7.500) = 4542 
    [ 7.500, 10.000) = 645 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 166 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.851 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     26.573 ms/op
     p(99.9990) =     30.229 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 9.376 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.008 ms/op
Iteration   1: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  19.267 ms/op
                 existUser·p0.9999: 25.093 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.303 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.667 ms/op
                 existUser·p0.9999: 23.908 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  19.723 ms/op
                 existUser·p0.9999: 23.992 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289051
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6682 
    [ 2.500,  5.000) = 276702 
    [ 5.000,  7.500) = 4680 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     19.299 ms/op
     p(99.9900) =     23.989 ms/op
     p(99.9990) =     25.595 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 8.349 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.012 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  18.402 ms/op
                 getUser·p0.9999: 20.577 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  10.183 ms/op
                 getUser·p0.9999: 27.403 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  14.551 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284496
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5389 
    [ 2.500,  5.000) = 271229 
    [ 5.000,  7.500) = 6628 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     25.905 ms/op
     p(99.9990) =     28.327 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 10.862 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
Iteration   1: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  20.346 ms/op
                 listUser·p0.9999: 25.763 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.056 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 19.566 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238592
  mean =      4.023 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 229302 
    [ 5.000,  7.500) = 6982 
    [ 7.500, 10.000) = 1514 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     15.408 ms/op
     p(99.9900) =     23.565 ms/op
     p(99.9990) =     26.300 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.453 ± 3.175  ops/ms
ClientPb.existUser                       thrpt       3   9.675 ± 1.517  ops/ms
ClientPb.getUser                         thrpt       3   9.583 ± 2.543  ops/ms
ClientPb.listUser                        thrpt       3   8.050 ± 1.434  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 0.936   ms/op
ClientPb.existUser                        avgt       3   3.255 ± 1.324   ms/op
ClientPb.getUser                          avgt       3   3.505 ± 1.065   ms/op
ClientPb.listUser                         avgt       3   3.912 ± 1.327   ms/op
ClientPb.createUser                     sample  280676   3.417 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.851           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.283           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.573           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.802           ms/op
ClientPb.existUser                      sample  289051   3.319 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.299           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.989           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  284496   3.372 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.501           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.959           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.905           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.508           ms/op
ClientPb.listUser                       sample  238592   4.023 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.408           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.565           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.345           ms/op
