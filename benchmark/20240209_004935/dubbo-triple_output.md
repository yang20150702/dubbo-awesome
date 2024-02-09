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
# Warmup Iteration   1: 4.910 ops/ms
# Warmup Iteration   2: 12.193 ops/ms
# Warmup Iteration   3: 12.602 ops/ms
Iteration   1: 12.837 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 12.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.919 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (12.837, 12.919, 12.981), stdev = 0.074
  CI (99.9%): [11.567, 14.271] (assumes normal distribution)


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
# Warmup Iteration   1: 8.421 ops/ms
# Warmup Iteration   2: 13.405 ops/ms
# Warmup Iteration   3: 13.094 ops/ms
Iteration   1: 13.376 ops/ms
Iteration   2: 13.279 ops/ms
Iteration   3: 13.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.353 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (13.279, 13.353, 13.404), stdev = 0.065
  CI (99.9%): [12.161, 14.545] (assumes normal distribution)


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
# Warmup Iteration   1: 8.110 ops/ms
# Warmup Iteration   2: 12.700 ops/ms
# Warmup Iteration   3: 12.903 ops/ms
Iteration   1: 13.030 ops/ms
Iteration   2: 12.520 ops/ms
Iteration   3: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.798 ±(99.9%) 4.711 ops/ms [Average]
  (min, avg, max) = (12.520, 12.798, 13.030), stdev = 0.258
  CI (99.9%): [8.087, 17.509] (assumes normal distribution)


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
# Warmup Iteration   1: 6.819 ops/ms
# Warmup Iteration   2: 10.639 ops/ms
# Warmup Iteration   3: 10.812 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.790 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (10.746, 10.790, 10.832), stdev = 0.043
  CI (99.9%): [10.000, 11.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.003 ms/op
Iteration   1: 2.500 ±(99.9%) 0.003 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.485 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.469, 2.485, 2.500), stdev = 0.015
  CI (99.9%): [2.209, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
Iteration   3: 2.394 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.405 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.394, 2.405, 2.425), stdev = 0.017
  CI (99.9%): [2.096, 2.714] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.003 ms/op
Iteration   1: 2.399 ±(99.9%) 0.005 ms/op
Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
Iteration   3: 2.387 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.399 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.387, 2.399, 2.409), stdev = 0.011
  CI (99.9%): [2.199, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
Iteration   3: 2.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (2.961, 2.979, 3.006), stdev = 0.024
  CI (99.9%): [2.545, 3.413] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  10.315 ms/op
                 createUser·p0.9999: 14.183 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.904 ms/op
                 createUser·p0.9999: 14.571 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 11.387 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381868
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 186076 
    [ 2.500,  3.750) = 192495 
    [ 3.750,  5.000) = 2535 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      8.557 ms/op
     p(99.9900) =     13.874 ms/op
     p(99.9990) =     15.200 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  5.906 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.237 ms/op
                 existUser·p0.9999: 12.203 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  7.365 ms/op
                 existUser·p0.9999: 11.754 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396234
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 202675 
    [ 2.500,  3.750) = 190082 
    [ 3.750,  5.000) = 2679 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.371 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.667 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.948 ms/op
                 getUser·p0.999:  10.649 ms/op
                 getUser·p0.9999: 18.315 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  6.735 ms/op
                 getUser·p0.9999: 13.273 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.776 ms/op
                 getUser·p0.9999: 12.222 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386612
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193393 
    [ 2.500,  3.750) = 188593 
    [ 3.750,  5.000) = 3747 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 147 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     19.632 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.009 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.532 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.375 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.283 ms/op
                 listUser·p0.9999: 11.406 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.762 ms/op
                 listUser·p0.9999: 11.417 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321800
  mean =      2.981 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 94703 
    [ 2.500,  3.750) = 189686 
    [ 3.750,  5.000) = 30731 
    [ 5.000,  6.250) = 5271 
    [ 6.250,  7.500) = 612 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     11.365 ms/op
     p(99.9990) =     12.097 ms/op
     p(99.9999) =     12.272 ms/op
    p(100.0000) =     12.272 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.919 ± 1.352  ops/ms
ClientPb.existUser                       thrpt       3  13.353 ± 1.192  ops/ms
ClientPb.getUser                         thrpt       3  12.798 ± 4.711  ops/ms
ClientPb.listUser                        thrpt       3  10.790 ± 0.791  ops/ms
ClientPb.createUser                       avgt       3   2.485 ± 0.276   ms/op
ClientPb.existUser                        avgt       3   2.405 ± 0.309   ms/op
ClientPb.getUser                          avgt       3   2.399 ± 0.200   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.434   ms/op
ClientPb.createUser                     sample  381868   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.908           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.557           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.874           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.254           ms/op
ClientPb.existUser                      sample  396234   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.867           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.371           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.993           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.828           ms/op
ClientPb.getUser                        sample  386612   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.745           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.274           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.759           ms/op
ClientPb.listUser                       sample  321800   2.981 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.790           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.272           ms/op
