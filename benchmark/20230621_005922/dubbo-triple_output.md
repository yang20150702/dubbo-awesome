# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.430 ops/ms
# Warmup Iteration   2: 3.616 ops/ms
# Warmup Iteration   3: 6.046 ops/ms
Iteration   1: 6.360 ops/ms
Iteration   2: 6.788 ops/ms
Iteration   3: 6.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.616 ±(99.9%) 4.120 ops/ms [Average]
  (min, avg, max) = (6.360, 6.616, 6.788), stdev = 0.226
  CI (99.9%): [2.496, 10.736] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 4.913 ops/ms
# Warmup Iteration   3: 6.117 ops/ms
Iteration   1: 6.898 ops/ms
Iteration   2: 6.608 ops/ms
Iteration   3: 6.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.820 ±(99.9%) 3.374 ops/ms [Average]
  (min, avg, max) = (6.608, 6.820, 6.952), stdev = 0.185
  CI (99.9%): [3.445, 10.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.837 ops/ms
# Warmup Iteration   2: 5.776 ops/ms
# Warmup Iteration   3: 6.679 ops/ms
Iteration   1: 6.416 ops/ms
Iteration   2: 6.735 ops/ms
Iteration   3: 6.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.700 ±(99.9%) 4.893 ops/ms [Average]
  (min, avg, max) = (6.416, 6.700, 6.949), stdev = 0.268
  CI (99.9%): [1.807, 11.593] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.902 ops/ms
# Warmup Iteration   2: 4.634 ops/ms
# Warmup Iteration   3: 5.675 ops/ms
Iteration   1: 5.578 ops/ms
Iteration   2: 5.752 ops/ms
Iteration   3: 5.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.745 ±(99.9%) 2.979 ops/ms [Average]
  (min, avg, max) = (5.578, 5.745, 5.905), stdev = 0.163
  CI (99.9%): [2.767, 8.724] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.737 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.072 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.009 ms/op
Iteration   1: 4.977 ±(99.9%) 0.010 ms/op
Iteration   2: 4.758 ±(99.9%) 0.012 ms/op
Iteration   3: 4.969 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.901 ±(99.9%) 2.267 ms/op [Average]
  (min, avg, max) = (4.758, 4.901, 4.977), stdev = 0.124
  CI (99.9%): [2.634, 7.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 14.309 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.750 ±(99.9%) 0.008 ms/op
Iteration   1: 4.511 ±(99.9%) 0.013 ms/op
Iteration   2: 4.565 ±(99.9%) 0.012 ms/op
Iteration   3: 4.805 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.627 ±(99.9%) 2.857 ms/op [Average]
  (min, avg, max) = (4.511, 4.627, 4.805), stdev = 0.157
  CI (99.9%): [1.770, 7.485] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.868 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.230 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.009 ms/op
Iteration   1: 4.770 ±(99.9%) 0.011 ms/op
Iteration   2: 5.043 ±(99.9%) 0.012 ms/op
Iteration   3: 4.742 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.852 ±(99.9%) 3.037 ms/op [Average]
  (min, avg, max) = (4.742, 4.852, 5.043), stdev = 0.166
  CI (99.9%): [1.814, 7.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.628 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.014 ms/op
Iteration   1: 5.768 ±(99.9%) 0.012 ms/op
Iteration   2: 5.734 ±(99.9%) 0.011 ms/op
Iteration   3: 5.606 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.703 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (5.606, 5.703, 5.768), stdev = 0.086
  CI (99.9%): [4.141, 7.265] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 16.251 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.395 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.326 ±(99.9%) 0.022 ms/op
Iteration   1: 4.718 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.976 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  25.141 ms/op
                 createUser·p0.9999: 32.047 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   2: 4.610 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.242 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  23.798 ms/op
                 createUser·p0.9999: 29.266 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 4.673 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.987 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  15.525 ms/op
                 createUser·p0.9999: 29.950 ms/op
                 createUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 205493
  mean =      4.667 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 164018 
    [ 5.000,  7.500) = 37425 
    [ 7.500, 10.000) = 2813 
    [10.000, 12.500) = 736 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     24.265 ms/op
     p(99.9900) =     31.243 ms/op
     p(99.9990) =     33.283 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 15.491 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.534 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.883 ±(99.9%) 0.018 ms/op
Iteration   1: 4.581 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   8.126 ms/op
                 existUser·p0.999:  17.407 ms/op
                 existUser·p0.9999: 30.050 ms/op
                 existUser·p1.00:   30.769 ms/op

Iteration   2: 4.516 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   8.208 ms/op
                 existUser·p0.999:  15.024 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 4.758 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.942 ms/op
                 existUser·p0.50:   4.547 ms/op
                 existUser·p0.90:   5.595 ms/op
                 existUser·p0.95:   6.357 ms/op
                 existUser·p0.99:   8.847 ms/op
                 existUser·p0.999:  25.231 ms/op
                 existUser·p0.9999: 28.877 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 207862
  mean =      4.616 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 171294 
    [ 5.000,  7.500) = 32357 
    [ 7.500, 10.000) = 3284 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     19.253 ms/op
     p(99.9900) =     29.433 ms/op
     p(99.9990) =     30.529 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 15.364 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.520 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.054 ±(99.9%) 0.017 ms/op
Iteration   1: 4.686 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   9.617 ms/op
                 getUser·p0.999:  18.049 ms/op
                 getUser·p0.9999: 33.358 ms/op
                 getUser·p1.00:   33.522 ms/op

Iteration   2: 4.733 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.084 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  13.402 ms/op
                 getUser·p0.9999: 27.885 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   3: 4.880 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   6.696 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  28.245 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 201352
  mean =      4.765 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 153167 
    [ 5.000,  7.500) = 42952 
    [ 7.500, 10.000) = 3910 
    [10.000, 12.500) = 825 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     25.372 ms/op
     p(99.9900) =     33.283 ms/op
     p(99.9990) =     33.816 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 15.385 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.657 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.809 ±(99.9%) 0.021 ms/op
Iteration   1: 5.592 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   10.809 ms/op
                 listUser·p0.999:  25.428 ms/op
                 listUser·p0.9999: 28.068 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   2: 5.460 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   6.234 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 27.461 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   3: 5.629 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  21.206 ms/op
                 listUser·p0.9999: 27.634 ms/op
                 listUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 172582
  mean =      5.560 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 43014 
    [ 5.000,  7.500) = 122629 
    [ 7.500, 10.000) = 4994 
    [10.000, 12.500) = 1136 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 113 

  Percentiles, ms/op:
      p(0.0000) =      2.638 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     27.738 ms/op
     p(99.9990) =     28.720 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.616 ± 4.120  ops/ms
ClientPb.existUser                       thrpt       3   6.820 ± 3.374  ops/ms
ClientPb.getUser                         thrpt       3   6.700 ± 4.893  ops/ms
ClientPb.listUser                        thrpt       3   5.745 ± 2.979  ops/ms
ClientPb.createUser                       avgt       3   4.901 ± 2.267   ms/op
ClientPb.existUser                        avgt       3   4.627 ± 2.857   ms/op
ClientPb.getUser                          avgt       3   4.852 ± 3.037   ms/op
ClientPb.listUser                         avgt       3   5.703 ± 1.562   ms/op
ClientPb.createUser                     sample  205493   4.667 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.976           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.569           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.265           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.243           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  207862   4.616 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.548           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.552           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.253           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.433           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.769           ms/op
ClientPb.getUser                        sample  201352   4.765 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.060           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.372           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.283           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  172582   5.560 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.406           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.289           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.478           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.738           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.934           ms/op
