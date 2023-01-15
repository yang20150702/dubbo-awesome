# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.535 ops/ms
# Warmup Iteration   2: 6.282 ops/ms
# Warmup Iteration   3: 9.265 ops/ms
Iteration   1: 9.939 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 9.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.970 ±(99.9%) 1.552 ops/ms [Average]
  (min, avg, max) = (9.905, 9.970, 10.066), stdev = 0.085
  CI (99.9%): [8.418, 11.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ops/ms
# Warmup Iteration   2: 9.551 ops/ms
# Warmup Iteration   3: 9.697 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.898 ops/ms
Iteration   3: 10.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.785 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (10.637, 10.785, 10.898), stdev = 0.134
  CI (99.9%): [8.337, 13.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.270 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 9.880 ops/ms
Iteration   1: 9.953 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.184 ±(99.9%) 4.022 ops/ms [Average]
  (min, avg, max) = (9.953, 10.184, 10.392), stdev = 0.220
  CI (99.9%): [6.162, 14.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 7.483 ops/ms
# Warmup Iteration   3: 8.532 ops/ms
Iteration   1: 8.443 ops/ms
Iteration   2: 8.474 ops/ms
Iteration   3: 8.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.542 ±(99.9%) 2.655 ops/ms [Average]
  (min, avg, max) = (8.443, 8.542, 8.709), stdev = 0.146
  CI (99.9%): [5.887, 11.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.388 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.006 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
Iteration   3: 3.111 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.146 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.111, 3.146, 3.206), stdev = 0.052
  CI (99.9%): [2.196, 4.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.346 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
Iteration   2: 3.289 ±(99.9%) 0.004 ms/op
Iteration   3: 3.065 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.159 ±(99.9%) 2.117 ms/op [Average]
  (min, avg, max) = (3.065, 3.159, 3.289), stdev = 0.116
  CI (99.9%): [1.043, 5.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.005 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.002 ms/op
Iteration   1: 3.205 ±(99.9%) 0.004 ms/op
Iteration   2: 3.055 ±(99.9%) 0.004 ms/op
Iteration   3: 3.258 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.173 ±(99.9%) 1.917 ms/op [Average]
  (min, avg, max) = (3.055, 3.173, 3.258), stdev = 0.105
  CI (99.9%): [1.256, 5.089] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.869 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.008 ms/op
Iteration   1: 3.659 ±(99.9%) 0.009 ms/op
Iteration   2: 3.638 ±(99.9%) 0.012 ms/op
Iteration   3: 3.606 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.635 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.606, 3.635, 3.659), stdev = 0.027
  CI (99.9%): [3.148, 4.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.658 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 22.179 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  13.796 ms/op
                 createUser·p0.9999: 23.234 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  14.881 ms/op
                 createUser·p0.9999: 19.612 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301979
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12647 
    [ 2.500,  5.000) = 284793 
    [ 5.000,  7.500) = 3725 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.176 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  11.468 ms/op
                 existUser·p0.9999: 20.080 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  13.956 ms/op
                 existUser·p0.9999: 21.906 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  9.067 ms/op
                 existUser·p0.9999: 21.686 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313946
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15203 
    [ 2.500,  5.000) = 293564 
    [ 5.000,  7.500) = 4442 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     11.683 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     22.699 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.460 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
Iteration   1: 3.316 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  17.282 ms/op
                 getUser·p0.9999: 25.440 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  20.199 ms/op
                 getUser·p0.9999: 28.959 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  13.664 ms/op
                 getUser·p0.9999: 18.807 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299480
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15781 
    [ 2.500,  5.000) = 275921 
    [ 5.000,  7.500) = 6651 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     17.059 ms/op
     p(99.9900) =     25.495 ms/op
     p(99.9990) =     29.459 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.627 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.012 ms/op
Iteration   1: 3.678 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   6.924 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 20.588 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 3.655 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.063 ms/op
                 listUser·p0.99:   6.308 ms/op
                 listUser·p0.999:  13.819 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.797 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258631
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 252698 
    [ 5.000,  7.500) = 4229 
    [ 7.500, 10.000) = 940 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     21.051 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.970 ± 1.552  ops/ms
ClientPb.existUser                       thrpt       3  10.785 ± 2.448  ops/ms
ClientPb.getUser                         thrpt       3  10.184 ± 4.022  ops/ms
ClientPb.listUser                        thrpt       3   8.542 ± 2.655  ops/ms
ClientPb.createUser                       avgt       3   3.146 ± 0.950   ms/op
ClientPb.existUser                        avgt       3   3.159 ± 2.117   ms/op
ClientPb.getUser                          avgt       3   3.173 ± 1.917   ms/op
ClientPb.listUser                         avgt       3   3.635 ± 0.487   ms/op
ClientPb.createUser                     sample  301979   3.178 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.031           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.844           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.348           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.019           ms/op
ClientPb.existUser                      sample  313946   3.058 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.683           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.594           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.003           ms/op
ClientPb.getUser                        sample  299480   3.204 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.059           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.495           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  258631   3.709 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.484           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.694           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.529           ms/op
