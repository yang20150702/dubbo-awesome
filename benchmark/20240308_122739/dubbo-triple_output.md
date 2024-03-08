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
# Warmup Iteration   1: 5.437 ops/ms
# Warmup Iteration   2: 12.093 ops/ms
# Warmup Iteration   3: 12.718 ops/ms
Iteration   1: 12.730 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 12.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.798 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (12.730, 12.798, 12.844), stdev = 0.060
  CI (99.9%): [11.707, 13.888] (assumes normal distribution)


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
# Warmup Iteration   1: 8.364 ops/ms
# Warmup Iteration   2: 13.276 ops/ms
# Warmup Iteration   3: 13.383 ops/ms
Iteration   1: 13.458 ops/ms
Iteration   2: 13.372 ops/ms
Iteration   3: 13.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.435 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (13.372, 13.435, 13.474), stdev = 0.055
  CI (99.9%): [12.428, 14.441] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.718 ops/ms
# Warmup Iteration   2: 12.925 ops/ms
# Warmup Iteration   3: 12.923 ops/ms
Iteration   1: 13.097 ops/ms
Iteration   2: 12.955 ops/ms
Iteration   3: 13.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.059 ±(99.9%) 1.660 ops/ms [Average]
  (min, avg, max) = (12.955, 13.059, 13.124), stdev = 0.091
  CI (99.9%): [11.398, 14.719] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.072 ops/ms
# Warmup Iteration   2: 10.623 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.722 ±(99.9%) 0.243 ops/ms [Average]
  (min, avg, max) = (10.707, 10.722, 10.730), stdev = 0.013
  CI (99.9%): [10.479, 10.965] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.003 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
Iteration   2: 2.465 ±(99.9%) 0.003 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.473 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (2.458, 2.473, 2.495), stdev = 0.020
  CI (99.9%): [2.115, 2.831] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.419, 2.426, 2.434), stdev = 0.008
  CI (99.9%): [2.289, 2.563] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.003 ms/op
Iteration   1: 2.428 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.440 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.428, 2.440, 2.452), stdev = 0.012
  CI (99.9%): [2.220, 2.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
Iteration   2: 2.917 ±(99.9%) 0.005 ms/op
Iteration   3: 2.939 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.937 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.917, 2.937, 2.954), stdev = 0.018
  CI (99.9%): [2.602, 3.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  10.561 ms/op
                 createUser·p0.9999: 14.128 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.397 ms/op
                 createUser·p0.9999: 13.107 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.125 ms/op
                 createUser·p0.9999: 10.229 ms/op
                 createUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383334
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 187104 
    [ 2.500,  3.750) = 191207 
    [ 3.750,  5.000) = 4063 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      8.181 ms/op
     p(99.9900) =     13.364 ms/op
     p(99.9990) =     14.634 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  5.267 ms/op
                 existUser·p0.9999: 13.524 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  7.828 ms/op
                 existUser·p0.9999: 12.583 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  7.770 ms/op
                 existUser·p0.9999: 11.581 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395923
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 199062 
    [ 2.500,  3.750) = 193857 
    [ 3.750,  5.000) = 2248 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     12.846 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  6.606 ms/op
                 getUser·p0.9999: 13.336 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 12.519 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  6.555 ms/op
                 getUser·p0.9999: 10.385 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391830
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 198598 
    [ 2.500,  3.750) = 189484 
    [ 3.750,  5.000) = 2877 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      7.044 ms/op
     p(99.9900) =     12.891 ms/op
     p(99.9990) =     13.613 ms/op
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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
Iteration   1: 2.924 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.371 ms/op
                 listUser·p0.9999: 11.209 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   2: 2.940 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.733 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   3: 2.932 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.073 ms/op
                 listUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327135
  mean =      2.932 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 105202 
    [ 2.500,  3.750) = 186508 
    [ 3.750,  5.000) = 28759 
    [ 5.000,  6.250) = 5386 
    [ 6.250,  7.500) = 497 
    [ 7.500,  8.750) = 216 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.304 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     12.432 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.798 ± 1.090  ops/ms
ClientPb.existUser                       thrpt       3  13.435 ± 1.007  ops/ms
ClientPb.getUser                         thrpt       3  13.059 ± 1.660  ops/ms
ClientPb.listUser                        thrpt       3  10.722 ± 0.243  ops/ms
ClientPb.createUser                       avgt       3   2.473 ± 0.358   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.137   ms/op
ClientPb.getUser                          avgt       3   2.440 ± 0.220   ms/op
ClientPb.listUser                         avgt       3   2.937 ± 0.334   ms/op
ClientPb.createUser                     sample  383334   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.622           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.181           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.364           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  395923   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.952           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.816           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.846           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.172           ms/op
ClientPb.getUser                        sample  391830   2.448 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.904           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  327135   2.932 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.304           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
