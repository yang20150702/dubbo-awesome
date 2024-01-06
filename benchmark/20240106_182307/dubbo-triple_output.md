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
# Warmup Iteration   1: 5.098 ops/ms
# Warmup Iteration   2: 11.927 ops/ms
# Warmup Iteration   3: 12.332 ops/ms
Iteration   1: 12.407 ops/ms
Iteration   2: 12.464 ops/ms
Iteration   3: 12.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.498 ±(99.9%) 2.037 ops/ms [Average]
  (min, avg, max) = (12.407, 12.498, 12.622), stdev = 0.112
  CI (99.9%): [10.460, 14.535] (assumes normal distribution)


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
# Warmup Iteration   1: 8.411 ops/ms
# Warmup Iteration   2: 12.782 ops/ms
# Warmup Iteration   3: 13.088 ops/ms
Iteration   1: 13.204 ops/ms
Iteration   2: 13.047 ops/ms
Iteration   3: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.115 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (13.047, 13.115, 13.204), stdev = 0.080
  CI (99.9%): [11.652, 14.579] (assumes normal distribution)


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
# Warmup Iteration   1: 7.742 ops/ms
# Warmup Iteration   2: 12.617 ops/ms
# Warmup Iteration   3: 12.794 ops/ms
Iteration   1: 12.957 ops/ms
Iteration   2: 12.873 ops/ms
Iteration   3: 12.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.933 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (12.873, 12.933, 12.970), stdev = 0.053
  CI (99.9%): [11.970, 13.896] (assumes normal distribution)


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
# Warmup Iteration   1: 6.666 ops/ms
# Warmup Iteration   2: 10.659 ops/ms
# Warmup Iteration   3: 10.818 ops/ms
Iteration   1: 10.892 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.835 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (10.799, 10.835, 10.892), stdev = 0.050
  CI (99.9%): [9.920, 11.750] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.003 ms/op
Iteration   1: 2.569 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.003 ms/op
Iteration   3: 2.554 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.550, 2.558, 2.569), stdev = 0.010
  CI (99.9%): [2.369, 2.746] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.445, 2.460, 2.474), stdev = 0.015
  CI (99.9%): [2.190, 2.731] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.469, 2.479, 2.490), stdev = 0.011
  CI (99.9%): [2.285, 2.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
Iteration   3: 2.998 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.995, 3.009, 3.035), stdev = 0.022
  CI (99.9%): [2.605, 3.414] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  10.795 ms/op
                 createUser·p0.9999: 13.374 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.506 ms/op
                 createUser·p0.999:  7.057 ms/op
                 createUser·p0.9999: 12.321 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.451 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 10.880 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381750
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 185424 
    [ 2.500,  3.750) = 191793 
    [ 3.750,  5.000) = 3458 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     12.908 ms/op
     p(99.9990) =     13.798 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.620 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.085 ms/op
                 existUser·p0.9999: 13.598 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.537 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.971 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 11.141 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390047
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 190756 
    [ 2.500,  3.750) = 195228 
    [ 3.750,  5.000) = 3029 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      7.019 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  8.967 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  7.222 ms/op
                 getUser·p0.9999: 13.207 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  8.177 ms/op
                 getUser·p0.9999: 11.080 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385187
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 191318 
    [ 2.500,  3.750) = 190240 
    [ 3.750,  5.000) = 2947 
    [ 5.000,  6.250) = 237 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      7.919 ms/op
     p(99.9900) =     13.328 ms/op
     p(99.9990) =     14.224 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.632 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.698 ms/op
                 listUser·p1.00:   12.943 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.220 ms/op
                 listUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316648
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 90892 
    [ 2.500,  3.750) = 184386 
    [ 3.750,  5.000) = 33478 
    [ 5.000,  6.250) = 6291 
    [ 6.250,  7.500) = 821 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.279 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     12.165 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.498 ± 2.037  ops/ms
ClientPb.existUser                       thrpt       3  13.115 ± 1.464  ops/ms
ClientPb.getUser                         thrpt       3  12.933 ± 0.963  ops/ms
ClientPb.listUser                        thrpt       3  10.835 ± 0.915  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.188   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.271   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.194   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.405   ms/op
ClientPb.createUser                     sample  381750   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.451           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.908           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.073           ms/op
ClientPb.existUser                      sample  390047   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.019           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.385           ms/op
ClientPb.getUser                        sample  385187   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.872           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.919           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.328           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  316648   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.822           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.279           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.943           ms/op
