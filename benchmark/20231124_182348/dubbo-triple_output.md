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
# Warmup Iteration   1: 4.134 ops/ms
# Warmup Iteration   2: 11.875 ops/ms
# Warmup Iteration   3: 12.149 ops/ms
Iteration   1: 12.332 ops/ms
Iteration   2: 12.428 ops/ms
Iteration   3: 12.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.410 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (12.332, 12.410, 12.471), stdev = 0.071
  CI (99.9%): [11.112, 13.708] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 7.361 ops/ms
# Warmup Iteration   2: 12.485 ops/ms
# Warmup Iteration   3: 12.641 ops/ms
Iteration   1: 12.800 ops/ms
Iteration   2: 12.702 ops/ms
Iteration   3: 12.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.772 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (12.702, 12.772, 12.814), stdev = 0.061
  CI (99.9%): [11.657, 13.887] (assumes normal distribution)


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
# Warmup Iteration   1: 7.172 ops/ms
# Warmup Iteration   2: 12.459 ops/ms
# Warmup Iteration   3: 12.477 ops/ms
Iteration   1: 12.564 ops/ms
Iteration   2: 12.553 ops/ms
Iteration   3: 12.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.561 ±(99.9%) 0.131 ops/ms [Average]
  (min, avg, max) = (12.553, 12.561, 12.567), stdev = 0.007
  CI (99.9%): [12.430, 12.693] (assumes normal distribution)


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
# Warmup Iteration   1: 6.615 ops/ms
# Warmup Iteration   2: 10.135 ops/ms
# Warmup Iteration   3: 10.501 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.390 ±(99.9%) 1.361 ops/ms [Average]
  (min, avg, max) = (10.337, 10.390, 10.476), stdev = 0.075
  CI (99.9%): [9.029, 11.751] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.233 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
Iteration   1: 2.560 ±(99.9%) 0.004 ms/op
Iteration   2: 2.619 ±(99.9%) 0.005 ms/op
Iteration   3: 2.587 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.589 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (2.560, 2.589, 2.619), stdev = 0.030
  CI (99.9%): [2.049, 3.128] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.513 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.502, 2.513, 2.523), stdev = 0.010
  CI (99.9%): [2.326, 2.699] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.551 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.538, 2.551, 2.570), stdev = 0.017
  CI (99.9%): [2.241, 2.861] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.078 ±(99.9%) 0.005 ms/op
Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
Iteration   3: 3.061 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.067 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.061, 3.067, 3.078), stdev = 0.009
  CI (99.9%): [2.894, 3.241] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.737 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.007 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  12.921 ms/op
                 createUser·p0.9999: 14.325 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 13.806 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 10.822 ms/op
                 createUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375237
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178530 
    [ 2.500,  5.000) = 195696 
    [ 5.000,  7.500) = 543 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      9.675 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  11.565 ms/op
                 existUser·p0.9999: 13.898 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  9.422 ms/op
                 existUser·p0.9999: 13.307 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  8.787 ms/op
                 existUser·p0.9999: 12.730 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383535
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 187794 
    [ 2.500,  3.750) = 191956 
    [ 3.750,  5.000) = 2879 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.879 ms/op
     p(99.9900) =     13.380 ms/op
     p(99.9990) =     14.131 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 13.899 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 13.509 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  9.054 ms/op
                 getUser·p0.9999: 10.863 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377754
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 184207 
    [ 2.500,  3.750) = 188381 
    [ 3.750,  5.000) = 4041 
    [ 5.000,  6.250) = 599 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     13.586 ms/op
     p(99.9990) =     14.052 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.663 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 10.676 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.302 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.513 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.723 ms/op
                 listUser·p0.9999: 10.919 ms/op
                 listUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315477
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 86620 
    [ 2.500,  3.750) = 187546 
    [ 3.750,  5.000) = 34063 
    [ 5.000,  6.250) = 5807 
    [ 6.250,  7.500) = 659 
    [ 7.500,  8.750) = 182 
    [ 8.750, 10.000) = 318 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.479 ms/op
     p(99.9900) =     10.755 ms/op
     p(99.9990) =     11.199 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.410 ± 1.298  ops/ms
ClientPb.existUser                       thrpt       3  12.772 ± 1.115  ops/ms
ClientPb.getUser                         thrpt       3  12.561 ± 0.131  ops/ms
ClientPb.listUser                        thrpt       3  10.390 ± 1.361  ops/ms
ClientPb.createUser                       avgt       3   2.589 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   2.513 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.551 ± 0.310   ms/op
ClientPb.listUser                         avgt       3   3.067 ± 0.173   ms/op
ClientPb.createUser                     sample  375237   2.556 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.675           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.926           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.413           ms/op
ClientPb.existUser                      sample  383535   2.501 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.744           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.879           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.380           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.189           ms/op
ClientPb.getUser                        sample  377754   2.539 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.011           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.586           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  315477   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.479           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.755           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.534           ms/op
