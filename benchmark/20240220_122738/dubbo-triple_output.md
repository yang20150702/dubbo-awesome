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
# Warmup Iteration   1: 5.143 ops/ms
# Warmup Iteration   2: 12.123 ops/ms
# Warmup Iteration   3: 12.600 ops/ms
Iteration   1: 12.735 ops/ms
Iteration   2: 12.772 ops/ms
Iteration   3: 12.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.673 ±(99.9%) 2.567 ops/ms [Average]
  (min, avg, max) = (12.512, 12.673, 12.772), stdev = 0.141
  CI (99.9%): [10.106, 15.240] (assumes normal distribution)


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
# Warmup Iteration   1: 8.079 ops/ms
# Warmup Iteration   2: 13.229 ops/ms
# Warmup Iteration   3: 13.084 ops/ms
Iteration   1: 12.967 ops/ms
Iteration   2: 13.174 ops/ms
Iteration   3: 12.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.036 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (12.967, 13.036, 13.174), stdev = 0.119
  CI (99.9%): [10.857, 15.216] (assumes normal distribution)


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
# Warmup Iteration   1: 7.909 ops/ms
# Warmup Iteration   2: 12.806 ops/ms
# Warmup Iteration   3: 12.787 ops/ms
Iteration   1: 12.864 ops/ms
Iteration   2: 12.765 ops/ms
Iteration   3: 12.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.829 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (12.765, 12.829, 12.864), stdev = 0.055
  CI (99.9%): [11.819, 13.840] (assumes normal distribution)


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
# Warmup Iteration   1: 6.843 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.495 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.642 ±(99.9%) 0.768 ops/ms [Average]
  (min, avg, max) = (10.614, 10.642, 10.690), stdev = 0.042
  CI (99.9%): [9.874, 11.410] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.003 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.551 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.526, 2.551, 2.566), stdev = 0.022
  CI (99.9%): [2.152, 2.949] (assumes normal distribution)


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.437 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (2.404, 2.437, 2.454), stdev = 0.028
  CI (99.9%): [1.918, 2.955] (assumes normal distribution)


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.468, 2.477, 2.483), stdev = 0.008
  CI (99.9%): [2.327, 2.626] (assumes normal distribution)


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.058 ms/op [Average]
  (min, avg, max) = (3.035, 3.039, 3.042), stdev = 0.003
  CI (99.9%): [2.981, 3.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.843 ms/op
                 createUser·p0.9999: 13.744 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  8.672 ms/op
                 createUser·p0.9999: 11.264 ms/op
                 createUser·p1.00:   11.846 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.866 ms/op
                 createUser·p0.999:  8.690 ms/op
                 createUser·p0.9999: 14.871 ms/op
                 createUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380125
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 183199 
    [ 2.500,  3.750) = 192177 
    [ 3.750,  5.000) = 3516 
    [ 5.000,  6.250) = 671 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     15.027 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  5.909 ms/op
                 existUser·p0.9999: 13.842 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  5.869 ms/op
                 existUser·p0.9999: 12.188 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.010 ms/op
                 existUser·p0.9999: 11.894 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390684
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 194237 
    [ 2.500,  3.750) = 193247 
    [ 3.750,  5.000) = 2614 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      5.554 ms/op
     p(99.9900) =     13.204 ms/op
     p(99.9990) =     14.405 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 14.005 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  8.655 ms/op
                 getUser·p0.9999: 12.278 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.983 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 12.665 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380246
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 187890 
    [ 2.500,  3.750) = 188034 
    [ 3.750,  5.000) = 3258 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     15.520 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.883 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.756 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 10.290 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.342 ms/op
                 listUser·p0.9999: 12.632 ms/op
                 listUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316431
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 87472 
    [ 2.500,  3.750) = 188562 
    [ 3.750,  5.000) = 33275 
    [ 5.000,  6.250) = 5841 
    [ 6.250,  7.500) = 496 
    [ 7.500,  8.750) = 284 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      8.971 ms/op
     p(99.9900) =     11.475 ms/op
     p(99.9990) =     13.342 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.673 ± 2.567  ops/ms
ClientPb.existUser                       thrpt       3  13.036 ± 2.179  ops/ms
ClientPb.getUser                         thrpt       3  12.829 ± 1.011  ops/ms
ClientPb.listUser                        thrpt       3  10.642 ± 0.768  ops/ms
ClientPb.createUser                       avgt       3   2.551 ± 0.398   ms/op
ClientPb.existUser                        avgt       3   2.437 ± 0.519   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.149   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.058   ms/op
ClientPb.createUser                     sample  380125   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.992           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.188           ms/op
ClientPb.existUser                      sample  390684   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.670           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  380246   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.603           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.667           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  316431   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.895           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.971           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.475           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.500           ms/op
