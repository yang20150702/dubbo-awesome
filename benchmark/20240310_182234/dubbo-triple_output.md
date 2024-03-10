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
# Warmup Iteration   1: 4.940 ops/ms
# Warmup Iteration   2: 12.484 ops/ms
# Warmup Iteration   3: 12.637 ops/ms
Iteration   1: 12.937 ops/ms
Iteration   2: 12.928 ops/ms
Iteration   3: 12.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.953 ±(99.9%) 0.680 ops/ms [Average]
  (min, avg, max) = (12.928, 12.953, 12.996), stdev = 0.037
  CI (99.9%): [12.274, 13.633] (assumes normal distribution)


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
# Warmup Iteration   1: 7.838 ops/ms
# Warmup Iteration   2: 13.479 ops/ms
# Warmup Iteration   3: 13.475 ops/ms
Iteration   1: 13.414 ops/ms
Iteration   2: 13.396 ops/ms
Iteration   3: 13.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.402 ±(99.9%) 0.194 ops/ms [Average]
  (min, avg, max) = (13.395, 13.402, 13.414), stdev = 0.011
  CI (99.9%): [13.208, 13.595] (assumes normal distribution)


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
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 12.813 ops/ms
# Warmup Iteration   3: 13.042 ops/ms
Iteration   1: 12.869 ops/ms
Iteration   2: 13.026 ops/ms
Iteration   3: 13.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.993 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (12.869, 12.993, 13.085), stdev = 0.112
  CI (99.9%): [10.955, 15.032] (assumes normal distribution)


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
# Warmup Iteration   1: 6.784 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.847 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 10.891 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.896 ±(99.9%) 0.251 ops/ms [Average]
  (min, avg, max) = (10.885, 10.896, 10.911), stdev = 0.014
  CI (99.9%): [10.645, 11.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.458 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.437, 2.458, 2.474), stdev = 0.019
  CI (99.9%): [2.109, 2.806] (assumes normal distribution)


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.004 ms/op
Iteration   1: 2.371 ±(99.9%) 0.004 ms/op
Iteration   2: 2.386 ±(99.9%) 0.003 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.389 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.371, 2.389, 2.410), stdev = 0.019
  CI (99.9%): [2.034, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.003 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.435 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.419, 2.435, 2.446), stdev = 0.014
  CI (99.9%): [2.182, 2.687] (assumes normal distribution)


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
Iteration   3: 2.971 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.962, 2.973, 2.986), stdev = 0.012
  CI (99.9%): [2.749, 3.197] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  6.094 ms/op
                 createUser·p0.9999: 13.334 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.896 ms/op
                 createUser·p0.999:  6.177 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  7.893 ms/op
                 createUser·p0.9999: 10.551 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391919
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 193633 
    [ 2.500,  3.750) = 194655 
    [ 3.750,  5.000) = 2764 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      7.817 ms/op
     p(99.9900) =     12.757 ms/op
     p(99.9990) =     13.618 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.601 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  6.119 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.296 ms/op
                 existUser·p0.999:  5.822 ms/op
                 existUser·p0.9999: 12.971 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.257 ms/op
                 existUser·p0.9999: 11.289 ms/op
                 existUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397274
  mean =      2.414 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 203047 
    [ 2.500,  3.750) = 190598 
    [ 3.750,  5.000) = 2476 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.517 ms/op
     p(99.9900) =     12.997 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  7.001 ms/op
                 getUser·p0.9999: 13.927 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  8.500 ms/op
                 getUser·p0.9999: 12.254 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  9.288 ms/op
                 getUser·p0.9999: 12.248 ms/op
                 getUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389299
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 196446 
    [ 2.500,  3.750) = 187592 
    [ 3.750,  5.000) = 4384 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.203 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     14.727 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
Iteration   1: 2.951 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.703 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.300 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.276 ms/op
                 listUser·p1.00:   10.994 ms/op

Iteration   2: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.711 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.666 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.940 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.127 ms/op
                 listUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325495
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 102806 
    [ 2.500,  3.750) = 187125 
    [ 3.750,  5.000) = 29305 
    [ 5.000,  6.250) = 4981 
    [ 6.250,  7.500) = 463 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 277 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     10.699 ms/op
     p(99.9990) =     11.554 ms/op
     p(99.9999) =     11.780 ms/op
    p(100.0000) =     11.780 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.953 ± 0.680  ops/ms
ClientPb.existUser                       thrpt       3  13.402 ± 0.194  ops/ms
ClientPb.getUser                         thrpt       3  12.993 ± 2.038  ops/ms
ClientPb.listUser                        thrpt       3  10.896 ± 0.251  ops/ms
ClientPb.createUser                       avgt       3   2.458 ± 0.348   ms/op
ClientPb.existUser                        avgt       3   2.389 ± 0.355   ms/op
ClientPb.getUser                          avgt       3   2.435 ± 0.252   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.224   ms/op
ClientPb.createUser                     sample  391919   2.447 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.817           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.757           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.729           ms/op
ClientPb.existUser                      sample  397274   2.414 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.997           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  389299   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.203           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.942           ms/op
ClientPb.listUser                       sample  325495   2.946 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.703           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.699           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.780           ms/op
