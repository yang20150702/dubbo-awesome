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
# Warmup Iteration   1: 4.940 ops/ms
# Warmup Iteration   2: 12.015 ops/ms
# Warmup Iteration   3: 12.200 ops/ms
Iteration   1: 12.553 ops/ms
Iteration   2: 12.470 ops/ms
Iteration   3: 12.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.567 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (12.470, 12.567, 12.678), stdev = 0.105
  CI (99.9%): [10.657, 14.478] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 12.888 ops/ms
# Warmup Iteration   3: 13.019 ops/ms
Iteration   1: 12.703 ops/ms
Iteration   2: 12.964 ops/ms
Iteration   3: 13.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.907 ±(99.9%) 3.333 ops/ms [Average]
  (min, avg, max) = (12.703, 12.907, 13.054), stdev = 0.183
  CI (99.9%): [9.574, 16.240] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ops/ms
# Warmup Iteration   2: 12.456 ops/ms
# Warmup Iteration   3: 12.867 ops/ms
Iteration   1: 12.517 ops/ms
Iteration   2: 12.730 ops/ms
Iteration   3: 12.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.646 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (12.517, 12.646, 12.730), stdev = 0.113
  CI (99.9%): [10.581, 14.711] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.026 ops/ms
# Warmup Iteration   2: 10.616 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 10.768 ops/ms
Iteration   2: 10.719 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.734 ±(99.9%) 0.543 ops/ms [Average]
  (min, avg, max) = (10.714, 10.734, 10.768), stdev = 0.030
  CI (99.9%): [10.191, 11.276] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.003 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (2.469, 2.491, 2.531), stdev = 0.034
  CI (99.9%): [1.865, 3.117] (assumes normal distribution)


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.003 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.455, 2.458, 2.465), stdev = 0.006
  CI (99.9%): [2.357, 2.560] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.463 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.451, 2.463, 2.474), stdev = 0.012
  CI (99.9%): [2.250, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
Iteration   3: 2.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (2.967, 2.989, 3.006), stdev = 0.020
  CI (99.9%): [2.631, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 13.604 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  8.963 ms/op
                 createUser·p0.9999: 11.765 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  7.997 ms/op
                 createUser·p0.9999: 10.420 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386643
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 187548 
    [ 2.500,  3.750) = 195389 
    [ 3.750,  5.000) = 2704 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.717 ms/op
     p(99.9000) =      8.053 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.275 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  5.498 ms/op
                 existUser·p0.9999: 13.189 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  8.210 ms/op
                 existUser·p0.9999: 11.961 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  9.408 ms/op
                 existUser·p0.9999: 10.961 ms/op
                 existUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388793
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 192632 
    [ 2.500,  3.750) = 191588 
    [ 3.750,  5.000) = 3323 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 156 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.462 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.960 ms/op
                 getUser·p0.999:  9.860 ms/op
                 getUser·p0.9999: 13.978 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.488 ms/op
                 getUser·p0.9999: 11.895 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  6.974 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387222
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 193766 
    [ 2.500,  3.750) = 187705 
    [ 3.750,  5.000) = 4063 
    [ 5.000,  6.250) = 1066 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      7.610 ms/op
     p(99.9900) =     14.013 ms/op
     p(99.9990) =     15.766 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.777 ms/op
                 listUser·p0.9999: 10.633 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.952 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.988 ms/op
                 listUser·p0.9999: 10.191 ms/op
                 listUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321473
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 100882 
    [ 2.500,  3.750) = 183022 
    [ 3.750,  5.000) = 30337 
    [ 5.000,  6.250) = 5852 
    [ 6.250,  7.500) = 614 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 288 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.069 ms/op
     p(99.9900) =     10.909 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.567 ± 1.910  ops/ms
ClientPb.existUser                       thrpt       3  12.907 ± 3.333  ops/ms
ClientPb.getUser                         thrpt       3  12.646 ± 2.065  ops/ms
ClientPb.listUser                        thrpt       3  10.734 ± 0.543  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.626   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.102   ms/op
ClientPb.getUser                          avgt       3   2.463 ± 0.212   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.357   ms/op
ClientPb.createUser                     sample  386643   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.750           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.717           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.053           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  388793   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.836           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.462           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.041           ms/op
ClientPb.getUser                        sample  387222   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.610           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.013           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.024           ms/op
ClientPb.listUser                       sample  321473   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.822           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.069           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.909           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.452           ms/op
