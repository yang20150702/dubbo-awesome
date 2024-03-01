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
# Warmup Iteration   1: 4.651 ops/ms
# Warmup Iteration   2: 11.933 ops/ms
# Warmup Iteration   3: 12.405 ops/ms
Iteration   1: 12.626 ops/ms
Iteration   2: 12.753 ops/ms
Iteration   3: 12.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.732 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (12.626, 12.732, 12.818), stdev = 0.098
  CI (99.9%): [10.951, 14.514] (assumes normal distribution)


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
# Warmup Iteration   1: 8.177 ops/ms
# Warmup Iteration   2: 13.146 ops/ms
# Warmup Iteration   3: 13.184 ops/ms
Iteration   1: 13.243 ops/ms
Iteration   2: 13.269 ops/ms
Iteration   3: 13.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.264 ±(99.9%) 0.341 ops/ms [Average]
  (min, avg, max) = (13.243, 13.264, 13.279), stdev = 0.019
  CI (99.9%): [12.923, 13.605] (assumes normal distribution)


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
# Warmup Iteration   1: 7.898 ops/ms
# Warmup Iteration   2: 12.477 ops/ms
# Warmup Iteration   3: 12.768 ops/ms
Iteration   1: 12.762 ops/ms
Iteration   2: 12.711 ops/ms
Iteration   3: 12.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.776 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (12.711, 12.776, 12.856), stdev = 0.073
  CI (99.9%): [11.436, 14.117] (assumes normal distribution)


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
# Warmup Iteration   1: 6.823 ops/ms
# Warmup Iteration   2: 10.555 ops/ms
# Warmup Iteration   3: 10.466 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.694 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.679 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (10.641, 10.679, 10.702), stdev = 0.033
  CI (99.9%): [10.082, 11.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.003 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.500, 2.513, 2.525), stdev = 0.012
  CI (99.9%): [2.288, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 3.503 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.393 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.373 ±(99.9%) 0.004 ms/op
Iteration   1: 2.396 ±(99.9%) 0.005 ms/op
Iteration   2: 2.396 ±(99.9%) 0.004 ms/op
Iteration   3: 2.369 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.387 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.369, 2.387, 2.396), stdev = 0.016
  CI (99.9%): [2.099, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.516, 2.521, 2.526), stdev = 0.005
  CI (99.9%): [2.435, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
Iteration   3: 3.033 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.014, 3.026, 3.033), stdev = 0.011
  CI (99.9%): [2.834, 3.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  10.258 ms/op
                 createUser·p0.9999: 13.877 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  10.179 ms/op
                 createUser·p0.9999: 12.460 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  8.854 ms/op
                 createUser·p0.9999: 11.108 ms/op
                 createUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382444
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 185285 
    [ 2.500,  3.750) = 192609 
    [ 3.750,  5.000) = 3497 
    [ 5.000,  6.250) = 446 
    [ 6.250,  7.500) = 128 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.856 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.126 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
Iteration   1: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  5.308 ms/op
                 existUser·p0.9999: 13.708 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  8.260 ms/op
                 existUser·p0.9999: 13.542 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 12.348 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394961
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 202702 
    [ 2.500,  3.750) = 188551 
    [ 3.750,  5.000) = 2720 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     13.148 ms/op
     p(99.9990) =     14.109 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  11.829 ms/op
                 getUser·p0.9999: 13.386 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  6.787 ms/op
                 getUser·p0.9999: 12.141 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  6.849 ms/op
                 getUser·p0.9999: 9.752 ms/op
                 getUser·p1.00:   10.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388002
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 195002 
    [ 2.500,  3.750) = 189061 
    [ 3.750,  5.000) = 3011 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     12.963 ms/op
     p(99.9990) =     13.596 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.417 ms/op
                 listUser·p0.9999: 11.082 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.080 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 13.331 ms/op
                 listUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320083
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 93614 
    [ 2.500,  3.750) = 187442 
    [ 3.750,  5.000) = 31906 
    [ 5.000,  6.250) = 5649 
    [ 6.250,  7.500) = 631 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.074 ms/op
     p(99.9990) =     14.002 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.732 ± 1.782  ops/ms
ClientPb.existUser                       thrpt       3  13.264 ± 0.341  ops/ms
ClientPb.getUser                         thrpt       3  12.776 ± 1.340  ops/ms
ClientPb.listUser                        thrpt       3  10.679 ± 0.597  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.387 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.086   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.193   ms/op
ClientPb.createUser                     sample  382444   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.652           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.856           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  394961   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.614           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.676           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.148           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.270           ms/op
ClientPb.getUser                        sample  388002   2.472 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.709           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.520           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.963           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.763           ms/op
ClientPb.listUser                       sample  320083   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.821           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.074           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
