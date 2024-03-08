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
# Warmup Iteration   1: 5.236 ops/ms
# Warmup Iteration   2: 12.144 ops/ms
# Warmup Iteration   3: 12.561 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.819 ops/ms
Iteration   3: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.791 ±(99.9%) 0.457 ops/ms [Average]
  (min, avg, max) = (12.770, 12.791, 12.819), stdev = 0.025
  CI (99.9%): [12.334, 13.249] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.784 ops/ms
# Warmup Iteration   2: 13.066 ops/ms
# Warmup Iteration   3: 13.130 ops/ms
Iteration   1: 13.413 ops/ms
Iteration   2: 13.339 ops/ms
Iteration   3: 13.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.343 ±(99.9%) 1.232 ops/ms [Average]
  (min, avg, max) = (13.278, 13.343, 13.413), stdev = 0.068
  CI (99.9%): [12.111, 14.575] (assumes normal distribution)


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
# Warmup Iteration   1: 8.147 ops/ms
# Warmup Iteration   2: 12.665 ops/ms
# Warmup Iteration   3: 12.840 ops/ms
Iteration   1: 13.021 ops/ms
Iteration   2: 12.825 ops/ms
Iteration   3: 12.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.922 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (12.825, 12.922, 13.021), stdev = 0.098
  CI (99.9%): [11.135, 14.710] (assumes normal distribution)


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
# Warmup Iteration   1: 7.112 ops/ms
# Warmup Iteration   2: 10.605 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 10.742 ops/ms
Iteration   2: 10.687 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.720 ±(99.9%) 0.530 ops/ms [Average]
  (min, avg, max) = (10.687, 10.720, 10.742), stdev = 0.029
  CI (99.9%): [10.190, 11.251] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.003 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.452 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (2.437, 2.452, 2.479), stdev = 0.023
  CI (99.9%): [2.024, 2.880] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.396 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.004 ms/op
Iteration   1: 2.408 ±(99.9%) 0.003 ms/op
Iteration   2: 2.380 ±(99.9%) 0.004 ms/op
Iteration   3: 2.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.392 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.380, 2.392, 2.408), stdev = 0.015
  CI (99.9%): [2.125, 2.660] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.454, 2.462, 2.468), stdev = 0.008
  CI (99.9%): [2.321, 2.604] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.005 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
Iteration   3: 2.959 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.956, 2.960, 2.965), stdev = 0.005
  CI (99.9%): [2.876, 3.043] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 13.369 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.541 ms/op
                 createUser·p0.999:  6.585 ms/op
                 createUser·p0.9999: 11.189 ms/op
                 createUser·p1.00:   11.420 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  7.332 ms/op
                 createUser·p0.9999: 9.940 ms/op
                 createUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391963
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 193929 
    [ 2.500,  3.750) = 194642 
    [ 3.750,  5.000) = 2291 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     13.038 ms/op
     p(99.9990) =     14.295 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.378 ±(99.9%) 0.005 ms/op
Iteration   1: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.218 ms/op
                 existUser·p0.9999: 16.960 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.412 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  8.496 ms/op
                 existUser·p0.9999: 12.069 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399919
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 201662 
    [ 2.500,  3.750) = 195732 
    [ 3.750,  5.000) = 1787 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.478 ms/op
     p(99.9000) =      6.878 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.006 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  5.706 ms/op
                 getUser·p0.9999: 13.712 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.962 ms/op
                 getUser·p0.9999: 12.819 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  5.525 ms/op
                 getUser·p0.9999: 13.369 ms/op
                 getUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391792
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 203411 
    [ 2.500,  3.750) = 182903 
    [ 3.750,  5.000) = 4477 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      7.809 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.190 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
Iteration   1: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.493 ms/op
                 listUser·p0.9999: 10.804 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.362 ms/op
                 listUser·p1.00:   14.057 ms/op

Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 10.434 ms/op
                 listUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325703
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 102633 
    [ 2.500,  3.750) = 187478 
    [ 3.750,  5.000) = 29017 
    [ 5.000,  6.250) = 5204 
    [ 6.250,  7.500) = 540 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 333 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.092 ms/op
     p(99.9990) =     12.770 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.791 ± 0.457  ops/ms
ClientPb.existUser                       thrpt       3  13.343 ± 1.232  ops/ms
ClientPb.getUser                         thrpt       3  12.922 ± 1.788  ops/ms
ClientPb.listUser                        thrpt       3  10.720 ± 0.530  ops/ms
ClientPb.createUser                       avgt       3   2.452 ± 0.428   ms/op
ClientPb.existUser                        avgt       3   2.392 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.142   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.083   ms/op
ClientPb.createUser                     sample  391963   2.447 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.887           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.970           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.038           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.680           ms/op
ClientPb.existUser                      sample  399919   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.821           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.878           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.137           ms/op
ClientPb.getUser                        sample  391792   2.448 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.809           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  325703   2.945 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.092           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.057           ms/op
