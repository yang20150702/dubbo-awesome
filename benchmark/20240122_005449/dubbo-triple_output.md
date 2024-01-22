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
# Warmup Iteration   1: 4.863 ops/ms
# Warmup Iteration   2: 11.994 ops/ms
# Warmup Iteration   3: 12.185 ops/ms
Iteration   1: 12.585 ops/ms
Iteration   2: 12.449 ops/ms
Iteration   3: 12.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.487 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (12.428, 12.487, 12.585), stdev = 0.085
  CI (99.9%): [10.931, 14.043] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.909 ops/ms
# Warmup Iteration   2: 12.819 ops/ms
# Warmup Iteration   3: 12.939 ops/ms
Iteration   1: 12.791 ops/ms
Iteration   2: 12.884 ops/ms
Iteration   3: 12.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.846 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (12.791, 12.846, 12.884), stdev = 0.049
  CI (99.9%): [11.957, 13.736] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.823 ops/ms
# Warmup Iteration   2: 12.659 ops/ms
# Warmup Iteration   3: 12.923 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 12.941 ops/ms
Iteration   3: 12.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.910 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (12.753, 12.910, 13.034), stdev = 0.143
  CI (99.9%): [10.300, 15.519] (assumes normal distribution)


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
# Warmup Iteration   1: 6.831 ops/ms
# Warmup Iteration   2: 10.457 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.556 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.559 ±(99.9%) 0.510 ops/ms [Average]
  (min, avg, max) = (10.533, 10.559, 10.588), stdev = 0.028
  CI (99.9%): [10.049, 11.069] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.003 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.482 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (2.457, 2.482, 2.500), stdev = 0.023
  CI (99.9%): [2.067, 2.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.418 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.418, 2.429, 2.439), stdev = 0.011
  CI (99.9%): [2.236, 2.623] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.003 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.510, 2.513, 2.519), stdev = 0.005
  CI (99.9%): [2.426, 2.600] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.703 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
Iteration   3: 3.064 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.057 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.040, 3.057, 3.066), stdev = 0.015
  CI (99.9%): [2.791, 3.322] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.006 ms/op
Iteration   1: 2.564 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  12.397 ms/op
                 createUser·p0.9999: 14.533 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   2: 2.588 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.764 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372273
  mean =      2.575 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 178017 
    [ 2.500,  3.750) = 190283 
    [ 3.750,  5.000) = 3162 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     15.324 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  6.375 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.079 ms/op
                 existUser·p0.9999: 12.943 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  9.000 ms/op
                 existUser·p0.9999: 11.931 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387325
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 190675 
    [ 2.500,  3.750) = 193803 
    [ 3.750,  5.000) = 2099 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     13.924 ms/op
     p(99.9990) =     14.891 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  12.409 ms/op
                 getUser·p0.9999: 14.205 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.074 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 13.454 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 12.679 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381332
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 186533 
    [ 2.500,  3.750) = 188872 
    [ 3.750,  5.000) = 4687 
    [ 5.000,  6.250) = 688 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      8.940 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.440 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.192 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.009 ms/op
Iteration   1: 3.103 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.609 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  8.945 ms/op
                 listUser·p0.9999: 11.033 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 3.096 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.792 ms/op
                 listUser·p1.00:   12.894 ms/op

Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.728 ms/op
                 listUser·p0.999:  10.102 ms/op
                 listUser·p0.9999: 15.122 ms/op
                 listUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309764
  mean =      3.096 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 77560 
    [ 2.500,  3.750) = 186432 
    [ 3.750,  5.000) = 36738 
    [ 5.000,  6.250) = 7393 
    [ 6.250,  7.500) = 855 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     12.944 ms/op
     p(99.9990) =     16.124 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.487 ± 1.556  ops/ms
ClientPb.existUser                       thrpt       3  12.846 ± 0.890  ops/ms
ClientPb.getUser                         thrpt       3  12.910 ± 2.609  ops/ms
ClientPb.listUser                        thrpt       3  10.559 ± 0.510  ops/ms
ClientPb.createUser                       avgt       3   2.482 ± 0.416   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.193   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.087   ms/op
ClientPb.listUser                         avgt       3   3.057 ± 0.266   ms/op
ClientPb.createUser                     sample  372273   2.575 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.451           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.417           ms/op
ClientPb.existUser                      sample  387325   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.897           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.094           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.924           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  381332   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.940           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.844           ms/op
ClientPb.listUser                       sample  309764   3.096 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.609           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.944           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.171           ms/op
