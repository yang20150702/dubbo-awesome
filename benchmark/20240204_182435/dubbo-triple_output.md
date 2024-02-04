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
# Warmup Iteration   1: 4.558 ops/ms
# Warmup Iteration   2: 12.353 ops/ms
# Warmup Iteration   3: 12.279 ops/ms
Iteration   1: 12.344 ops/ms
Iteration   2: 12.550 ops/ms
Iteration   3: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.536 ±(99.9%) 3.377 ops/ms [Average]
  (min, avg, max) = (12.344, 12.536, 12.713), stdev = 0.185
  CI (99.9%): [9.158, 15.913] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.967 ops/ms
# Warmup Iteration   2: 12.984 ops/ms
# Warmup Iteration   3: 13.041 ops/ms
Iteration   1: 12.907 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.961 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (12.907, 12.961, 13.009), stdev = 0.051
  CI (99.9%): [12.023, 13.899] (assumes normal distribution)


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
# Warmup Iteration   1: 7.392 ops/ms
# Warmup Iteration   2: 12.520 ops/ms
# Warmup Iteration   3: 12.717 ops/ms
Iteration   1: 12.697 ops/ms
Iteration   2: 12.645 ops/ms
Iteration   3: 12.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.690 ±(99.9%) 0.785 ops/ms [Average]
  (min, avg, max) = (12.645, 12.690, 12.730), stdev = 0.043
  CI (99.9%): [11.905, 13.476] (assumes normal distribution)


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
# Warmup Iteration   1: 6.558 ops/ms
# Warmup Iteration   2: 10.388 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.726 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.732 ±(99.9%) 0.217 ops/ms [Average]
  (min, avg, max) = (10.725, 10.732, 10.746), stdev = 0.012
  CI (99.9%): [10.515, 10.949] (assumes normal distribution)


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.497, 2.502, 2.508), stdev = 0.006
  CI (99.9%): [2.395, 2.610] (assumes normal distribution)


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.450, 2.457, 2.470), stdev = 0.011
  CI (99.9%): [2.253, 2.661] (assumes normal distribution)


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.468, 2.488, 2.506), stdev = 0.019
  CI (99.9%): [2.147, 2.830] (assumes normal distribution)


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.004 ms/op
Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
Iteration   3: 2.999 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.986, 2.996, 3.003), stdev = 0.009
  CI (99.9%): [2.839, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.718 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  11.048 ms/op
                 createUser·p0.9999: 15.013 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.133 ms/op
                 createUser·p0.9999: 12.346 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.387 ms/op
                 createUser·p0.9999: 10.709 ms/op
                 createUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380236
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 183263 
    [ 2.500,  3.750) = 193518 
    [ 3.750,  5.000) = 2699 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.450 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     15.670 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.663 ms/op
                 existUser·p0.9999: 13.810 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  7.935 ms/op
                 existUser·p0.9999: 13.021 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.889 ms/op
                 existUser·p0.9999: 11.435 ms/op
                 existUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390110
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 195715 
    [ 2.500,  3.750) = 191324 
    [ 3.750,  5.000) = 2323 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      7.580 ms/op
     p(99.9900) =     13.336 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.494 ms/op
                 getUser·p0.999:  6.420 ms/op
                 getUser·p0.9999: 13.355 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.465 ms/op
                 getUser·p0.999:  7.955 ms/op
                 getUser·p0.9999: 12.524 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.860 ms/op
                 getUser·p0.999:  7.386 ms/op
                 getUser·p0.9999: 9.734 ms/op
                 getUser·p1.00:   10.240 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388476
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 194546 
    [ 2.500,  3.750) = 190672 
    [ 3.750,  5.000) = 2407 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.571 ms/op
     p(99.9900) =     12.913 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.683 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.640 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  8.777 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317639
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 91496 
    [ 2.500,  3.750) = 186758 
    [ 3.750,  5.000) = 31627 
    [ 5.000,  6.250) = 6334 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.033 ms/op
     p(99.9900) =     11.342 ms/op
     p(99.9990) =     12.762 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.536 ± 3.377  ops/ms
ClientPb.existUser                       thrpt       3  12.961 ± 0.938  ops/ms
ClientPb.getUser                         thrpt       3  12.690 ± 0.785  ops/ms
ClientPb.listUser                        thrpt       3  10.732 ± 0.217  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.107   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.204   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.341   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.157   ms/op
ClientPb.createUser                     sample  380236   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.450           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.761           ms/op
ClientPb.existUser                      sample  390110   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.580           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.336           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  388476   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.645           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.571           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.913           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.713           ms/op
ClientPb.listUser                       sample  317639   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.033           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.342           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.140           ms/op
