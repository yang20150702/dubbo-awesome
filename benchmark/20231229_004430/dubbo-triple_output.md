# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.042 ops/ms
# Warmup Iteration   2: 12.361 ops/ms
# Warmup Iteration   3: 12.427 ops/ms
Iteration   1: 12.597 ops/ms
Iteration   2: 12.709 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.708 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (12.597, 12.708, 12.819), stdev = 0.111
  CI (99.9%): [10.680, 14.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.908 ops/ms
# Warmup Iteration   2: 12.991 ops/ms
# Warmup Iteration   3: 13.107 ops/ms
Iteration   1: 13.095 ops/ms
Iteration   2: 13.171 ops/ms
Iteration   3: 13.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.133 ±(99.9%) 0.697 ops/ms [Average]
  (min, avg, max) = (13.095, 13.133, 13.171), stdev = 0.038
  CI (99.9%): [12.436, 13.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.008 ops/ms
# Warmup Iteration   2: 12.582 ops/ms
# Warmup Iteration   3: 12.902 ops/ms
Iteration   1: 12.852 ops/ms
Iteration   2: 12.922 ops/ms
Iteration   3: 12.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.912 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (12.852, 12.912, 12.962), stdev = 0.056
  CI (99.9%): [11.894, 13.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ops/ms
# Warmup Iteration   2: 10.453 ops/ms
# Warmup Iteration   3: 10.668 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.711 ops/ms
Iteration   3: 10.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.718 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (10.671, 10.718, 10.771), stdev = 0.050
  CI (99.9%): [9.803, 11.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (2.491, 2.512, 2.548), stdev = 0.031
  CI (99.9%): [1.939, 3.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.443, 2.450, 2.457), stdev = 0.007
  CI (99.9%): [2.329, 2.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (2.473, 2.500, 2.518), stdev = 0.024
  CI (99.9%): [2.066, 2.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.851 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.996, 3.007, 3.014), stdev = 0.009
  CI (99.9%): [2.834, 3.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.536 ms/op
                 createUser·p0.999:  10.936 ms/op
                 createUser·p0.9999: 13.340 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  9.708 ms/op
                 createUser·p0.9999: 11.956 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.097 ms/op
                 createUser·p0.9999: 11.111 ms/op
                 createUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383269
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 186485 
    [ 2.500,  3.750) = 193227 
    [ 3.750,  5.000) = 2699 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.506 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.272 ms/op
                 existUser·p0.9999: 15.385 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392997
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 196325 
    [ 2.500,  3.750) = 193465 
    [ 3.750,  5.000) = 2357 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      6.210 ms/op
     p(99.9900) =     14.003 ms/op
     p(99.9990) =     15.965 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  12.401 ms/op
                 getUser·p0.9999: 22.488 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  7.892 ms/op
                 getUser·p0.9999: 13.352 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  8.086 ms/op
                 getUser·p0.9999: 10.682 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380920
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186748 
    [ 2.500,  5.000) = 192957 
    [ 5.000,  7.500) = 780 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     14.464 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.802 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.906 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.823 ms/op
                 listUser·p0.9999: 11.585 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 10.875 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319081
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 91156 
    [ 2.500,  3.750) = 190159 
    [ 3.750,  5.000) = 30753 
    [ 5.000,  6.250) = 5573 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 174 
    [ 8.750, 10.000) = 315 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.536 ms/op
     p(99.9990) =     12.318 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.708 ± 2.028  ops/ms
ClientPb.existUser                       thrpt       3  13.133 ± 0.697  ops/ms
ClientPb.getUser                         thrpt       3  12.912 ± 1.018  ops/ms
ClientPb.listUser                        thrpt       3  10.718 ± 0.915  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.573   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.121   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.435   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.173   ms/op
ClientPb.createUser                     sample  383269   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.987           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.102           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.927           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.303           ms/op
ClientPb.existUser                      sample  392997   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.871           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.210           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.003           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.941           ms/op
ClientPb.getUser                        sample  380920   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.086           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.464           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.708           ms/op
ClientPb.listUser                       sample  319081   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
