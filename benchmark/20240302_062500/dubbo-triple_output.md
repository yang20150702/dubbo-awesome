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
# Warmup Iteration   1: 4.944 ops/ms
# Warmup Iteration   2: 12.103 ops/ms
# Warmup Iteration   3: 12.627 ops/ms
Iteration   1: 12.993 ops/ms
Iteration   2: 12.932 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.942 ±(99.9%) 0.859 ops/ms [Average]
  (min, avg, max) = (12.900, 12.942, 12.993), stdev = 0.047
  CI (99.9%): [12.083, 13.801] (assumes normal distribution)


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
# Warmup Iteration   1: 8.574 ops/ms
# Warmup Iteration   2: 13.433 ops/ms
# Warmup Iteration   3: 13.415 ops/ms
Iteration   1: 13.562 ops/ms
Iteration   2: 13.495 ops/ms
Iteration   3: 13.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.522 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (13.495, 13.522, 13.562), stdev = 0.035
  CI (99.9%): [12.882, 14.162] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ops/ms
# Warmup Iteration   2: 12.639 ops/ms
# Warmup Iteration   3: 12.862 ops/ms
Iteration   1: 12.732 ops/ms
Iteration   2: 13.025 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.935 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (12.732, 12.935, 13.047), stdev = 0.176
  CI (99.9%): [9.727, 16.143] (assumes normal distribution)


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
# Warmup Iteration   1: 6.763 ops/ms
# Warmup Iteration   2: 10.620 ops/ms
# Warmup Iteration   3: 10.750 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.716 ±(99.9%) 0.450 ops/ms [Average]
  (min, avg, max) = (10.691, 10.716, 10.740), stdev = 0.025
  CI (99.9%): [10.266, 11.166] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.474 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.451, 2.474, 2.496), stdev = 0.023
  CI (99.9%): [2.062, 2.885] (assumes normal distribution)


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.395 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.352 ±(99.9%) 0.003 ms/op
Iteration   2: 2.375 ±(99.9%) 0.003 ms/op
Iteration   3: 2.374 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.367 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.352, 2.367, 2.375), stdev = 0.013
  CI (99.9%): [2.130, 2.604] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (2.432, 2.447, 2.462), stdev = 0.015
  CI (99.9%): [2.173, 2.720] (assumes normal distribution)


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
Iteration   3: 2.966 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.960, 2.964, 2.966), stdev = 0.003
  CI (99.9%): [2.908, 3.019] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 17.703 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 12.653 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.009 ms/op
                 createUser·p0.9999: 11.802 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381228
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 184385 
    [ 2.500,  3.750) = 193110 
    [ 3.750,  5.000) = 2875 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.843 ms/op
     p(99.9900) =     13.498 ms/op
     p(99.9990) =     18.303 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  9.526 ms/op
                 existUser·p0.9999: 14.093 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.120 ms/op
                 existUser·p0.9999: 12.121 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.555 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386374
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 186247 
    [ 2.500,  3.750) = 196982 
    [ 3.750,  5.000) = 2347 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      7.493 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.584 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  7.271 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  6.325 ms/op
                 getUser·p0.9999: 12.599 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  7.810 ms/op
                 getUser·p0.9999: 12.550 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386965
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193191 
    [ 2.500,  3.750) = 188298 
    [ 3.750,  5.000) = 4271 
    [ 5.000,  6.250) = 702 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      7.168 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.009 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.340 ms/op
                 listUser·p0.9999: 10.779 ms/op
                 listUser·p1.00:   11.239 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.251 ms/op
                 listUser·p0.9999: 10.949 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   3: 3.031 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.675 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 13.302 ms/op
                 listUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319801
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 97323 
    [ 2.500,  3.750) = 183975 
    [ 3.750,  5.000) = 30374 
    [ 5.000,  6.250) = 6511 
    [ 6.250,  7.500) = 806 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.691 ms/op
     p(99.9990) =     13.487 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.942 ± 0.859  ops/ms
ClientPb.existUser                       thrpt       3  13.522 ± 0.640  ops/ms
ClientPb.getUser                         thrpt       3  12.935 ± 3.208  ops/ms
ClientPb.listUser                        thrpt       3  10.716 ± 0.450  ops/ms
ClientPb.createUser                       avgt       3   2.474 ± 0.411   ms/op
ClientPb.existUser                        avgt       3   2.367 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.273   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.056   ms/op
ClientPb.createUser                     sample  381228   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.819           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.843           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.498           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.776           ms/op
ClientPb.existUser                      sample  386374   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.000           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.493           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.795           ms/op
ClientPb.getUser                        sample  386965   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.168           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.975           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.957           ms/op
ClientPb.listUser                       sample  319801   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.675           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.691           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
