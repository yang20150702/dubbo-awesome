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
# Warmup Iteration   1: 5.149 ops/ms
# Warmup Iteration   2: 12.053 ops/ms
# Warmup Iteration   3: 12.510 ops/ms
Iteration   1: 12.619 ops/ms
Iteration   2: 12.639 ops/ms
Iteration   3: 12.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.705 ±(99.9%) 2.388 ops/ms [Average]
  (min, avg, max) = (12.619, 12.705, 12.855), stdev = 0.131
  CI (99.9%): [10.316, 15.093] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.241 ops/ms
# Warmup Iteration   2: 13.009 ops/ms
# Warmup Iteration   3: 13.036 ops/ms
Iteration   1: 12.920 ops/ms
Iteration   2: 13.051 ops/ms
Iteration   3: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.996 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (12.920, 12.996, 13.051), stdev = 0.068
  CI (99.9%): [11.756, 14.237] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.866 ops/ms
# Warmup Iteration   2: 12.562 ops/ms
# Warmup Iteration   3: 12.976 ops/ms
Iteration   1: 12.969 ops/ms
Iteration   2: 13.039 ops/ms
Iteration   3: 13.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.022 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (12.969, 13.022, 13.058), stdev = 0.047
  CI (99.9%): [12.166, 13.879] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.890 ops/ms
# Warmup Iteration   2: 10.705 ops/ms
# Warmup Iteration   3: 10.824 ops/ms
Iteration   1: 10.857 ops/ms
Iteration   2: 10.821 ops/ms
Iteration   3: 10.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.833 ±(99.9%) 0.384 ops/ms [Average]
  (min, avg, max) = (10.820, 10.833, 10.857), stdev = 0.021
  CI (99.9%): [10.449, 11.216] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.003 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.480, 2.498, 2.516), stdev = 0.018
  CI (99.9%): [2.175, 2.821] (assumes normal distribution)


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.004 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.406, 2.423, 2.434), stdev = 0.015
  CI (99.9%): [2.151, 2.695] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.469, 2.478, 2.486), stdev = 0.009
  CI (99.9%): [2.320, 2.635] (assumes normal distribution)


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
Iteration   1: 2.954 ±(99.9%) 0.005 ms/op
Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
Iteration   3: 2.938 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.944 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.938, 2.944, 2.954), stdev = 0.009
  CI (99.9%): [2.776, 3.112] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  11.221 ms/op
                 createUser·p0.9999: 13.783 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  9.551 ms/op
                 createUser·p0.9999: 12.080 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.735 ms/op
                 createUser·p0.999:  7.844 ms/op
                 createUser·p0.9999: 11.278 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381226
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 184320 
    [ 2.500,  3.750) = 193601 
    [ 3.750,  5.000) = 2636 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.178 ms/op
     p(99.9900) =     13.154 ms/op
     p(99.9990) =     14.273 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.684 ms/op
                 existUser·p0.9999: 13.585 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  8.207 ms/op
                 existUser·p0.9999: 13.043 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  8.482 ms/op
                 existUser·p0.9999: 11.766 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386942
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189156 
    [ 2.500,  3.750) = 194174 
    [ 3.750,  5.000) = 2682 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      7.965 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  11.256 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 14.800 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 10.548 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379181
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 186127 
    [ 2.500,  3.750) = 187606 
    [ 3.750,  5.000) = 4357 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.402 ms/op
     p(99.9900) =     14.044 ms/op
     p(99.9990) =     15.306 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.006 ms/op
                 listUser·p0.9999: 10.518 ms/op
                 listUser·p1.00:   10.699 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.220 ms/op
                 listUser·p0.9999: 11.894 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.207 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316259
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 87639 
    [ 2.500,  3.750) = 189045 
    [ 3.750,  5.000) = 32425 
    [ 5.000,  6.250) = 5709 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 321 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.590 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     12.449 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.705 ± 2.388  ops/ms
ClientPb.existUser                       thrpt       3  12.996 ± 1.241  ops/ms
ClientPb.getUser                         thrpt       3  13.022 ± 0.856  ops/ms
ClientPb.listUser                        thrpt       3  10.833 ± 0.384  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.323   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.272   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.158   ms/op
ClientPb.listUser                         avgt       3   2.944 ± 0.168   ms/op
ClientPb.createUser                     sample  381226   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.178           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.154           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  386942   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.965           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  379181   2.529 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.879           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.402           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.044           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.417           ms/op
ClientPb.listUser                       sample  316259   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.893           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.590           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
