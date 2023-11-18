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
# Warmup Iteration   1: 5.169 ops/ms
# Warmup Iteration   2: 12.690 ops/ms
# Warmup Iteration   3: 12.754 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 13.054 ops/ms
Iteration   3: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.963 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (12.846, 12.963, 13.054), stdev = 0.106
  CI (99.9%): [11.022, 14.905] (assumes normal distribution)


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
# Warmup Iteration   1: 8.228 ops/ms
# Warmup Iteration   2: 13.264 ops/ms
# Warmup Iteration   3: 13.284 ops/ms
Iteration   1: 13.273 ops/ms
Iteration   2: 13.341 ops/ms
Iteration   3: 13.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.249 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (13.134, 13.249, 13.341), stdev = 0.105
  CI (99.9%): [11.326, 15.173] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ops/ms
# Warmup Iteration   2: 12.893 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 13.089 ops/ms
Iteration   2: 13.129 ops/ms
Iteration   3: 13.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.080 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (13.023, 13.080, 13.129), stdev = 0.054
  CI (99.9%): [12.104, 14.057] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 10.729 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.819 ops/ms
Iteration   3: 10.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.866 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (10.819, 10.866, 10.908), stdev = 0.044
  CI (99.9%): [10.054, 11.677] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.003 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.500, 2.505, 2.513), stdev = 0.007
  CI (99.9%): [2.374, 2.636] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.004 ms/op
Iteration   1: 2.413 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.417 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.413, 2.417, 2.420), stdev = 0.004
  CI (99.9%): [2.349, 2.485] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.438 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.430, 2.438, 2.443), stdev = 0.007
  CI (99.9%): [2.302, 2.574] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.726 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.007 ms/op
Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
Iteration   3: 2.965 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.952, 2.960, 2.965), stdev = 0.007
  CI (99.9%): [2.828, 3.092] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 11.519 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.202 ms/op
                 createUser·p0.9999: 10.603 ms/op
                 createUser·p1.00:   10.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385888
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 187048 
    [ 2.500,  3.750) = 194720 
    [ 3.750,  5.000) = 3026 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     12.842 ms/op
     p(99.9990) =     13.809 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 3.627 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.174 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.695 ms/op
                 existUser·p0.9999: 12.449 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 12.579 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394567
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 197788 
    [ 2.500,  3.750) = 193339 
    [ 3.750,  5.000) = 2657 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      6.349 ms/op
     p(99.9900) =     13.132 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.455 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  6.342 ms/op
                 getUser·p0.9999: 11.927 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  7.723 ms/op
                 getUser·p0.9999: 10.766 ms/op
                 getUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389401
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 194165 
    [ 2.500,  3.750) = 190980 
    [ 3.750,  5.000) = 3141 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.388 ms/op
     p(99.9900) =     13.683 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
Iteration   1: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.845 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.197 ms/op
                 listUser·p0.9999: 13.126 ms/op
                 listUser·p1.00:   13.304 ms/op

Iteration   2: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  10.207 ms/op
                 listUser·p0.9999: 13.903 ms/op
                 listUser·p1.00:   14.598 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.940 ms/op
                 listUser·p0.9999: 10.428 ms/op
                 listUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323056
  mean =      2.969 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 100176 
    [ 2.500,  3.750) = 186345 
    [ 3.750,  5.000) = 29442 
    [ 5.000,  6.250) = 5752 
    [ 6.250,  7.500) = 521 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.256 ms/op
     p(99.9900) =     13.135 ms/op
     p(99.9990) =     14.393 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.963 ± 1.941  ops/ms
ClientPb.existUser                       thrpt       3  13.249 ± 1.923  ops/ms
ClientPb.getUser                         thrpt       3  13.080 ± 0.977  ops/ms
ClientPb.listUser                        thrpt       3  10.866 ± 0.811  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.131   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.068   ms/op
ClientPb.getUser                          avgt       3   2.438 ± 0.136   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.132   ms/op
ClientPb.createUser                     sample  385888   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.842           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.466           ms/op
ClientPb.existUser                      sample  394567   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.349           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.132           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.926           ms/op
ClientPb.getUser                        sample  389401   2.463 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.455           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.388           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.683           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  323056   2.969 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.256           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.135           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.598           ms/op
