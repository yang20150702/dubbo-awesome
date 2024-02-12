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
# Warmup Iteration   1: 5.175 ops/ms
# Warmup Iteration   2: 12.027 ops/ms
# Warmup Iteration   3: 12.359 ops/ms
Iteration   1: 12.634 ops/ms
Iteration   2: 12.566 ops/ms
Iteration   3: 12.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.619 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (12.566, 12.619, 12.655), stdev = 0.047
  CI (99.9%): [11.765, 13.473] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ops/ms
# Warmup Iteration   2: 13.026 ops/ms
# Warmup Iteration   3: 13.090 ops/ms
Iteration   1: 13.115 ops/ms
Iteration   2: 13.111 ops/ms
Iteration   3: 13.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.113 ±(99.9%) 0.040 ops/ms [Average]
  (min, avg, max) = (13.111, 13.113, 13.115), stdev = 0.002
  CI (99.9%): [13.073, 13.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.017 ops/ms
# Warmup Iteration   2: 12.752 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.867 ops/ms
Iteration   2: 12.726 ops/ms
Iteration   3: 12.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.756 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (12.674, 12.756, 12.867), stdev = 0.100
  CI (99.9%): [10.933, 14.578] (assumes normal distribution)


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
# Warmup Iteration   1: 6.655 ops/ms
# Warmup Iteration   2: 10.575 ops/ms
# Warmup Iteration   3: 10.704 ops/ms
Iteration   1: 10.669 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.723 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (10.669, 10.723, 10.788), stdev = 0.060
  CI (99.9%): [9.625, 11.822] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.527, 2.542, 2.554), stdev = 0.013
  CI (99.9%): [2.298, 2.786] (assumes normal distribution)


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.003 ms/op
Iteration   1: 2.423 ±(99.9%) 0.003 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (2.423, 2.439, 2.451), stdev = 0.014
  CI (99.9%): [2.186, 2.692] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.455 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.441, 2.455, 2.465), stdev = 0.012
  CI (99.9%): [2.232, 2.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
Iteration   3: 2.962 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.962 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (2.940, 2.962, 2.984), stdev = 0.022
  CI (99.9%): [2.559, 3.365] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  10.969 ms/op
                 createUser·p0.9999: 14.012 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  9.235 ms/op
                 createUser·p0.9999: 12.780 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.198 ms/op
                 createUser·p0.9999: 12.465 ms/op
                 createUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383169
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 186390 
    [ 2.500,  3.750) = 193093 
    [ 3.750,  5.000) = 2838 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.289 ms/op
     p(99.9900) =     13.381 ms/op
     p(99.9990) =     14.191 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  6.507 ms/op
                 existUser·p0.9999: 16.090 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.332 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 11.998 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388152
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 191738 
    [ 2.500,  3.750) = 192844 
    [ 3.750,  5.000) = 2589 
    [ 5.000,  6.250) = 464 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.765 ms/op
     p(99.9900) =     13.539 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  7.283 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  7.677 ms/op
                 getUser·p0.9999: 12.601 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  6.296 ms/op
                 getUser·p0.9999: 11.892 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388199
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 193390 
    [ 2.500,  3.750) = 191002 
    [ 3.750,  5.000) = 3027 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      7.263 ms/op
     p(99.9900) =     13.192 ms/op
     p(99.9990) =     14.078 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.715 ms/op
                 listUser·p0.9999: 13.174 ms/op
                 listUser·p1.00:   15.532 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.539 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 12.048 ms/op
                 listUser·p1.00:   13.206 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 11.282 ms/op
                 listUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319684
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 96138 
    [ 2.500,  3.750) = 184628 
    [ 3.750,  5.000) = 31869 
    [ 5.000,  6.250) = 5704 
    [ 6.250,  7.500) = 571 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 191 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.568 ms/op
     p(99.9990) =     14.054 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.619 ± 0.854  ops/ms
ClientPb.existUser                       thrpt       3  13.113 ± 0.040  ops/ms
ClientPb.getUser                         thrpt       3  12.756 ± 1.822  ops/ms
ClientPb.listUser                        thrpt       3  10.723 ± 1.099  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.244   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.253   ms/op
ClientPb.getUser                          avgt       3   2.455 ± 0.223   ms/op
ClientPb.listUser                         avgt       3   2.962 ± 0.403   ms/op
ClientPb.createUser                     sample  383169   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.991           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.289           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  388152   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.785           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.539           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.924           ms/op
ClientPb.getUser                        sample  388199   2.471 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.263           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.192           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  319684   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.539           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.568           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.532           ms/op
