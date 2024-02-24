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
# Warmup Iteration   1: 4.990 ops/ms
# Warmup Iteration   2: 12.120 ops/ms
# Warmup Iteration   3: 12.513 ops/ms
Iteration   1: 12.546 ops/ms
Iteration   2: 12.565 ops/ms
Iteration   3: 12.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.488 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (12.352, 12.488, 12.565), stdev = 0.118
  CI (99.9%): [10.340, 14.636] (assumes normal distribution)


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
# Warmup Iteration   1: 8.157 ops/ms
# Warmup Iteration   2: 13.094 ops/ms
# Warmup Iteration   3: 13.016 ops/ms
Iteration   1: 13.076 ops/ms
Iteration   2: 13.032 ops/ms
Iteration   3: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.041 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (13.016, 13.041, 13.076), stdev = 0.031
  CI (99.9%): [12.479, 13.604] (assumes normal distribution)


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
# Warmup Iteration   1: 7.883 ops/ms
# Warmup Iteration   2: 12.585 ops/ms
# Warmup Iteration   3: 12.717 ops/ms
Iteration   1: 12.958 ops/ms
Iteration   2: 12.705 ops/ms
Iteration   3: 12.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.795 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (12.705, 12.795, 12.958), stdev = 0.142
  CI (99.9%): [10.213, 15.377] (assumes normal distribution)


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
# Warmup Iteration   1: 6.860 ops/ms
# Warmup Iteration   2: 10.400 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.531 ops/ms
Iteration   2: 10.545 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.557 ±(99.9%) 0.609 ops/ms [Average]
  (min, avg, max) = (10.531, 10.557, 10.595), stdev = 0.033
  CI (99.9%): [9.947, 11.166] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.571 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.532, 2.550, 2.571), stdev = 0.019
  CI (99.9%): [2.197, 2.904] (assumes normal distribution)


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.003 ms/op
Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.414, 2.436, 2.458), stdev = 0.022
  CI (99.9%): [2.040, 2.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.541 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.531, 2.541, 2.556), stdev = 0.014
  CI (99.9%): [2.294, 2.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.005 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
Iteration   3: 3.083 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.073 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.064, 3.073, 3.083), stdev = 0.010
  CI (99.9%): [2.900, 3.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.735 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
Iteration   1: 2.600 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  11.735 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 15.157 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.886 ms/op
                 createUser·p0.9999: 12.148 ms/op
                 createUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372644
  mean =      2.574 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 177163 
    [ 2.500,  3.750) = 190615 
    [ 3.750,  5.000) = 3882 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      9.039 ms/op
     p(99.9900) =     14.082 ms/op
     p(99.9990) =     15.553 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 13.427 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  7.980 ms/op
                 existUser·p0.9999: 12.026 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383859
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 185898 
    [ 2.500,  3.750) = 194682 
    [ 3.750,  5.000) = 2391 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      6.907 ms/op
     p(99.9900) =     13.357 ms/op
     p(99.9990) =     14.145 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  11.826 ms/op
                 getUser·p0.9999: 13.787 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.829 ms/op
                 getUser·p0.9999: 13.257 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  8.693 ms/op
                 getUser·p0.9999: 11.491 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379561
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187509 
    [ 2.500,  3.750) = 186353 
    [ 3.750,  5.000) = 4418 
    [ 5.000,  6.250) = 775 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      8.838 ms/op
     p(99.9900) =     13.288 ms/op
     p(99.9990) =     14.012 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
Iteration   1: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 10.276 ms/op
                 listUser·p1.00:   11.026 ms/op

Iteration   2: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.437 ms/op
                 listUser·p0.9999: 11.916 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.303 ms/op
                 listUser·p0.9999: 14.011 ms/op
                 listUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318031
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 91577 
    [ 2.500,  3.750) = 186714 
    [ 3.750,  5.000) = 32169 
    [ 5.000,  6.250) = 6052 
    [ 6.250,  7.500) = 737 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     12.953 ms/op
     p(99.9990) =     14.204 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.488 ± 2.148  ops/ms
ClientPb.existUser                       thrpt       3  13.041 ± 0.562  ops/ms
ClientPb.getUser                         thrpt       3  12.795 ± 2.582  ops/ms
ClientPb.listUser                        thrpt       3  10.557 ± 0.609  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.353   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.396   ms/op
ClientPb.getUser                          avgt       3   2.541 ± 0.247   ms/op
ClientPb.listUser                         avgt       3   3.073 ± 0.173   ms/op
ClientPb.createUser                     sample  372644   2.574 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.082           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.663           ms/op
ClientPb.existUser                      sample  383859   2.498 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.791           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.907           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.357           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  379561   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.980           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.838           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.288           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.057           ms/op
ClientPb.listUser                       sample  318031   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.953           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.270           ms/op
