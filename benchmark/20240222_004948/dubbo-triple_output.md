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
# Warmup Iteration   1: 5.047 ops/ms
# Warmup Iteration   2: 12.002 ops/ms
# Warmup Iteration   3: 12.479 ops/ms
Iteration   1: 12.732 ops/ms
Iteration   2: 12.565 ops/ms
Iteration   3: 12.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.672 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (12.565, 12.672, 12.732), stdev = 0.093
  CI (99.9%): [10.977, 14.367] (assumes normal distribution)


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
# Warmup Iteration   1: 7.747 ops/ms
# Warmup Iteration   2: 13.289 ops/ms
# Warmup Iteration   3: 13.183 ops/ms
Iteration   1: 13.318 ops/ms
Iteration   2: 13.154 ops/ms
Iteration   3: 13.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.192 ±(99.9%) 2.032 ops/ms [Average]
  (min, avg, max) = (13.105, 13.192, 13.318), stdev = 0.111
  CI (99.9%): [11.160, 15.224] (assumes normal distribution)


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
# Warmup Iteration   1: 7.852 ops/ms
# Warmup Iteration   2: 12.543 ops/ms
# Warmup Iteration   3: 12.629 ops/ms
Iteration   1: 12.762 ops/ms
Iteration   2: 12.689 ops/ms
Iteration   3: 12.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.746 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (12.689, 12.746, 12.788), stdev = 0.051
  CI (99.9%): [11.807, 13.685] (assumes normal distribution)


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
# Warmup Iteration   1: 6.720 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.681 ±(99.9%) 0.126 ops/ms [Average]
  (min, avg, max) = (10.674, 10.681, 10.688), stdev = 0.007
  CI (99.9%): [10.554, 10.807] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.503, 2.512, 2.523), stdev = 0.010
  CI (99.9%): [2.324, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
Iteration   3: 2.423 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.421, 2.426, 2.434), stdev = 0.007
  CI (99.9%): [2.300, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.488, 2.493, 2.497), stdev = 0.005
  CI (99.9%): [2.403, 2.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
Iteration   3: 2.986 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.990 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.977, 2.990, 3.007), stdev = 0.015
  CI (99.9%): [2.710, 3.269] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.314 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  11.793 ms/op
                 createUser·p0.9999: 13.882 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  9.780 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.486 ms/op
                 createUser·p0.9999: 10.048 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381819
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 184778 
    [ 2.500,  3.750) = 193741 
    [ 3.750,  5.000) = 2538 
    [ 5.000,  6.250) = 279 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.552 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.825 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  7.783 ms/op
                 existUser·p0.9999: 12.426 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.825 ms/op
                 existUser·p0.9999: 12.269 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392013
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 193375 
    [ 2.500,  3.750) = 195975 
    [ 3.750,  5.000) = 2031 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.485 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.485 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 13.940 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  10.663 ms/op
                 getUser·p0.9999: 12.769 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  8.881 ms/op
                 getUser·p0.9999: 10.833 ms/op
                 getUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381379
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 187517 
    [ 2.500,  3.750) = 188252 
    [ 3.750,  5.000) = 4451 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      8.960 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.722 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.602 ms/op
                 listUser·p0.999:  9.150 ms/op
                 listUser·p0.9999: 10.448 ms/op
                 listUser·p1.00:   11.239 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.698 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.836 ms/op
                 listUser·p0.9999: 12.172 ms/op
                 listUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321355
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 95338 
    [ 2.500,  3.750) = 189497 
    [ 3.750,  5.000) = 29749 
    [ 5.000,  6.250) = 5375 
    [ 6.250,  7.500) = 531 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.630 ms/op
     p(99.9990) =     14.230 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.672 ± 1.695  ops/ms
ClientPb.existUser                       thrpt       3  13.192 ± 2.032  ops/ms
ClientPb.getUser                         thrpt       3  12.746 ± 0.939  ops/ms
ClientPb.listUser                        thrpt       3  10.681 ± 0.126  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.188   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.090   ms/op
ClientPb.listUser                         avgt       3   2.990 ± 0.280   ms/op
ClientPb.createUser                     sample  381819   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.692           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.487           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  392013   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.722           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.485           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.849           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.927           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.648           ms/op
ClientPb.getUser                        sample  381379   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.722           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.960           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.320           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.811           ms/op
ClientPb.listUser                       sample  321355   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.630           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.451           ms/op
