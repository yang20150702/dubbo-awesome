# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ops/ms
# Warmup Iteration   2: 11.584 ops/ms
# Warmup Iteration   3: 11.845 ops/ms
Iteration   1: 12.377 ops/ms
Iteration   2: 12.383 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.419 ±(99.9%) 1.247 ops/ms [Average]
  (min, avg, max) = (12.377, 12.419, 12.498), stdev = 0.068
  CI (99.9%): [11.173, 13.666] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.035 ops/ms
# Warmup Iteration   2: 12.958 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 12.837 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.830 ±(99.9%) 0.567 ops/ms [Average]
  (min, avg, max) = (12.796, 12.830, 12.857), stdev = 0.031
  CI (99.9%): [12.263, 13.397] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.426 ops/ms
# Warmup Iteration   2: 12.458 ops/ms
# Warmup Iteration   3: 12.477 ops/ms
Iteration   1: 12.529 ops/ms
Iteration   2: 12.465 ops/ms
Iteration   3: 12.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.512 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (12.465, 12.512, 12.542), stdev = 0.041
  CI (99.9%): [11.763, 13.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.208 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.376 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.402 ±(99.9%) 0.654 ops/ms [Average]
  (min, avg, max) = (10.376, 10.402, 10.442), stdev = 0.036
  CI (99.9%): [9.748, 11.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.385 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.004 ms/op
Iteration   1: 2.596 ±(99.9%) 0.004 ms/op
Iteration   2: 2.608 ±(99.9%) 0.004 ms/op
Iteration   3: 2.621 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.608 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.596, 2.608, 2.621), stdev = 0.012
  CI (99.9%): [2.385, 2.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.480 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.463, 2.480, 2.489), stdev = 0.014
  CI (99.9%): [2.216, 2.744] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.003 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.513, 2.521, 2.532), stdev = 0.010
  CI (99.9%): [2.337, 2.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.004 ms/op
Iteration   1: 3.071 ±(99.9%) 0.005 ms/op
Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
Iteration   3: 3.059 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.059 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.049, 3.059, 3.071), stdev = 0.011
  CI (99.9%): [2.861, 3.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.316 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.604 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 13.889 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.537 ms/op
                 createUser·p0.9999: 11.806 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.617 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  6.569 ms/op
                 createUser·p0.9999: 11.895 ms/op
                 createUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368803
  mean =      2.600 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 174582 
    [ 2.500,  3.750) = 189878 
    [ 3.750,  5.000) = 3557 
    [ 5.000,  6.250) = 369 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      6.817 ms/op
     p(99.9900) =     13.128 ms/op
     p(99.9990) =     14.690 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.759 ms/op
                 existUser·p0.9999: 15.177 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  9.744 ms/op
                 existUser·p0.9999: 14.086 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.646 ms/op
                 existUser·p0.90:   3.138 ms/op
                 existUser·p0.95:   3.277 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  9.567 ms/op
                 existUser·p0.9999: 12.222 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 376968
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 182148 
    [ 2.500,  3.750) = 190612 
    [ 3.750,  5.000) = 3163 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     14.013 ms/op
     p(99.9990) =     15.281 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  11.640 ms/op
                 getUser·p0.9999: 14.094 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.195 ms/op
                 getUser·p0.95:   3.408 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  10.902 ms/op
                 getUser·p0.9999: 14.135 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 12.510 ms/op
                 getUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374491
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 179446 
    [ 2.500,  3.750) = 188807 
    [ 3.750,  5.000) = 5186 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     14.050 ms/op
     p(99.9990) =     14.628 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.981 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.899 ms/op
                 listUser·p0.9999: 12.842 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.872 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   3: 3.084 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.971 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311761
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 79059 
    [ 2.500,  3.750) = 189927 
    [ 3.750,  5.000) = 34357 
    [ 5.000,  6.250) = 6773 
    [ 6.250,  7.500) = 849 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     12.039 ms/op
     p(99.9990) =     12.991 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.419 ± 1.247  ops/ms
ClientPb.existUser                       thrpt       3  12.830 ± 0.567  ops/ms
ClientPb.getUser                         thrpt       3  12.512 ± 0.749  ops/ms
ClientPb.listUser                        thrpt       3  10.402 ± 0.654  ops/ms
ClientPb.createUser                       avgt       3   2.608 ± 0.223   ms/op
ClientPb.existUser                        avgt       3   2.480 ± 0.264   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.184   ms/op
ClientPb.listUser                         avgt       3   3.059 ± 0.198   ms/op
ClientPb.createUser                     sample  368803   2.600 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.035           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.817           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.128           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.828           ms/op
ClientPb.existUser                      sample  376968   2.543 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.143           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.450           ms/op
ClientPb.getUser                        sample  374491   2.561 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.159           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.050           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.909           ms/op
ClientPb.listUser                       sample  311761   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.898           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.039           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
