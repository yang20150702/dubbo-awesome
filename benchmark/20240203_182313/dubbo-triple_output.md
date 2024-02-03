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
# Warmup Iteration   1: 4.740 ops/ms
# Warmup Iteration   2: 11.791 ops/ms
# Warmup Iteration   3: 12.132 ops/ms
Iteration   1: 12.334 ops/ms
Iteration   2: 12.262 ops/ms
Iteration   3: 12.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.325 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (12.262, 12.325, 12.379), stdev = 0.059
  CI (99.9%): [11.246, 13.405] (assumes normal distribution)


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
# Warmup Iteration   1: 8.035 ops/ms
# Warmup Iteration   2: 12.790 ops/ms
# Warmup Iteration   3: 12.882 ops/ms
Iteration   1: 12.756 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.825 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (12.756, 12.825, 12.881), stdev = 0.064
  CI (99.9%): [11.660, 13.991] (assumes normal distribution)


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
# Warmup Iteration   1: 7.634 ops/ms
# Warmup Iteration   2: 12.348 ops/ms
# Warmup Iteration   3: 12.586 ops/ms
Iteration   1: 12.671 ops/ms
Iteration   2: 12.675 ops/ms
Iteration   3: 12.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 0.492 ops/ms [Average]
  (min, avg, max) = (12.671, 12.689, 12.720), stdev = 0.027
  CI (99.9%): [12.196, 13.181] (assumes normal distribution)


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
# Warmup Iteration   1: 6.783 ops/ms
# Warmup Iteration   2: 10.226 ops/ms
# Warmup Iteration   3: 10.367 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.495 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (10.456, 10.495, 10.550), stdev = 0.049
  CI (99.9%): [9.607, 11.384] (assumes normal distribution)


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.005 ms/op
Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
Iteration   3: 2.569 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.556, 2.565, 2.570), stdev = 0.008
  CI (99.9%): [2.420, 2.710] (assumes normal distribution)


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.452 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.452, 2.470, 2.492), stdev = 0.020
  CI (99.9%): [2.099, 2.841] (assumes normal distribution)


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.492, 2.497, 2.503), stdev = 0.006
  CI (99.9%): [2.397, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
Iteration   3: 3.004 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.998, 3.007, 3.019), stdev = 0.011
  CI (99.9%): [2.804, 3.210] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.579 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.761 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 14.090 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 12.698 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.584 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  8.624 ms/op
                 createUser·p0.9999: 10.748 ms/op
                 createUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372003
  mean =      2.578 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 176276 
    [ 2.500,  3.750) = 191540 
    [ 3.750,  5.000) = 3116 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.639 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  5.472 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  7.420 ms/op
                 existUser·p0.9999: 13.829 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  7.151 ms/op
                 existUser·p0.9999: 10.699 ms/op
                 existUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389570
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 206391 
    [ 2.500,  3.750) = 178694 
    [ 3.750,  5.000) = 3520 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      6.295 ms/op
     p(99.9900) =     13.288 ms/op
     p(99.9990) =     14.802 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  10.225 ms/op
                 getUser·p0.9999: 13.621 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   5.031 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 15.092 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  8.851 ms/op
                 getUser·p0.9999: 14.016 ms/op
                 getUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379056
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 185393 
    [ 2.500,  3.750) = 187704 
    [ 3.750,  5.000) = 4216 
    [ 5.000,  6.250) = 1152 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      8.928 ms/op
     p(99.9900) =     14.387 ms/op
     p(99.9990) =     15.650 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  10.479 ms/op
                 listUser·p0.9999: 12.401 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.209 ms/op
                 listUser·p0.9999: 11.085 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.393 ms/op
                 listUser·p0.9999: 11.133 ms/op
                 listUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314858
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 86590 
    [ 2.500,  3.750) = 186291 
    [ 3.750,  5.000) = 33697 
    [ 5.000,  6.250) = 6609 
    [ 6.250,  7.500) = 781 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.669 ms/op
     p(99.9900) =     11.928 ms/op
     p(99.9990) =     14.769 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.325 ± 1.079  ops/ms
ClientPb.existUser                       thrpt       3  12.825 ± 1.165  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 0.492  ops/ms
ClientPb.listUser                        thrpt       3  10.495 ± 0.888  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.145   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.371   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.101   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.203   ms/op
ClientPb.createUser                     sample  372003   2.578 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.820           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.060           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  389570   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.641           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.417           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.295           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.288           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  379056   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.763           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.928           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.387           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.712           ms/op
ClientPb.listUser                       sample  314858   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.669           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.928           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.367           ms/op
