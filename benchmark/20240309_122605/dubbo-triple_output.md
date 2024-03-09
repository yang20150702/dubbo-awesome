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
# Warmup Iteration   1: 4.629 ops/ms
# Warmup Iteration   2: 12.206 ops/ms
# Warmup Iteration   3: 12.751 ops/ms
Iteration   1: 12.881 ops/ms
Iteration   2: 13.017 ops/ms
Iteration   3: 12.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.922 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (12.867, 12.922, 13.017), stdev = 0.083
  CI (99.9%): [11.415, 14.428] (assumes normal distribution)


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
# Warmup Iteration   1: 8.807 ops/ms
# Warmup Iteration   2: 13.244 ops/ms
# Warmup Iteration   3: 13.440 ops/ms
Iteration   1: 13.510 ops/ms
Iteration   2: 13.574 ops/ms
Iteration   3: 13.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.433 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (13.214, 13.433, 13.574), stdev = 0.192
  CI (99.9%): [9.933, 16.932] (assumes normal distribution)


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
# Warmup Iteration   1: 7.693 ops/ms
# Warmup Iteration   2: 12.906 ops/ms
# Warmup Iteration   3: 13.057 ops/ms
Iteration   1: 13.219 ops/ms
Iteration   2: 13.099 ops/ms
Iteration   3: 13.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.141 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (13.099, 13.141, 13.219), stdev = 0.068
  CI (99.9%): [11.902, 14.379] (assumes normal distribution)


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
# Warmup Iteration   1: 6.961 ops/ms
# Warmup Iteration   2: 10.622 ops/ms
# Warmup Iteration   3: 10.835 ops/ms
Iteration   1: 10.853 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.851 ±(99.9%) 0.317 ops/ms [Average]
  (min, avg, max) = (10.832, 10.851, 10.867), stdev = 0.017
  CI (99.9%): [10.534, 11.167] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.003 ms/op
Iteration   3: 2.489 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.477, 2.499, 2.530), stdev = 0.028
  CI (99.9%): [1.994, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.003 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.398 ±(99.9%) 0.003 ms/op
Iteration   3: 2.399 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.409 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.398, 2.409, 2.429), stdev = 0.018
  CI (99.9%): [2.082, 2.735] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.445 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.438, 2.445, 2.459), stdev = 0.012
  CI (99.9%): [2.235, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 2.930 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.930, 2.951, 2.973), stdev = 0.022
  CI (99.9%): [2.555, 3.347] (assumes normal distribution)


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  6.442 ms/op
                 createUser·p0.9999: 13.502 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  9.677 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 11.768 ms/op
                 createUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384377
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 186397 
    [ 2.500,  3.750) = 194115 
    [ 3.750,  5.000) = 3003 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     12.945 ms/op
     p(99.9990) =     14.046 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.696 ms/op
                 existUser·p0.999:  5.586 ms/op
                 existUser·p0.9999: 13.251 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.222 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.175 ms/op
                 existUser·p0.9999: 12.220 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394994
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 198757 
    [ 2.500,  5.000) = 195530 
    [ 5.000,  7.500) = 315 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      6.743 ms/op
     p(99.9900) =     13.591 ms/op
     p(99.9990) =     20.714 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 13.351 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.358 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  7.558 ms/op
                 getUser·p0.9999: 10.928 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392121
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 198762 
    [ 2.500,  3.750) = 189014 
    [ 3.750,  5.000) = 3400 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 173 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.725 ms/op
     p(99.9900) =     13.038 ms/op
     p(99.9990) =     14.523 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.445 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 10.401 ms/op
                 listUser·p1.00:   11.190 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.032 ms/op
                 listUser·p0.9999: 11.468 ms/op
                 listUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319180
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 93309 
    [ 2.500,  3.750) = 186292 
    [ 3.750,  5.000) = 32488 
    [ 5.000,  6.250) = 5760 
    [ 6.250,  7.500) = 540 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.034 ms/op
     p(99.9990) =     12.293 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.922 ± 1.506  ops/ms
ClientPb.existUser                       thrpt       3  13.433 ± 3.499  ops/ms
ClientPb.getUser                         thrpt       3  13.141 ± 1.239  ops/ms
ClientPb.listUser                        thrpt       3  10.851 ± 0.317  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.505   ms/op
ClientPb.existUser                        avgt       3   2.409 ± 0.327   ms/op
ClientPb.getUser                          avgt       3   2.445 ± 0.211   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.396   ms/op
ClientPb.createUser                     sample  384377   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.759           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.945           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  394994   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.893           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.591           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.873           ms/op
ClientPb.getUser                        sample  392121   2.446 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.691           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.725           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.038           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  319180   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.034           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.812           ms/op
