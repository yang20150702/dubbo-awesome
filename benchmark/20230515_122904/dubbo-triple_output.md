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
# Warmup Iteration   1: 1.396 ops/ms
# Warmup Iteration   2: 3.054 ops/ms
# Warmup Iteration   3: 6.512 ops/ms
Iteration   1: 6.734 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.444 ±(99.9%) 11.435 ops/ms [Average]
  (min, avg, max) = (6.734, 7.444, 7.922), stdev = 0.627
  CI (99.9%): [≈ 0, 18.879] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.310 ops/ms
# Warmup Iteration   2: 6.947 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 8.216 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.084 ±(99.9%) 2.202 ops/ms [Average]
  (min, avg, max) = (7.981, 8.084, 8.216), stdev = 0.121
  CI (99.9%): [5.882, 10.285] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.000 ops/ms
# Warmup Iteration   2: 6.637 ops/ms
# Warmup Iteration   3: 7.506 ops/ms
Iteration   1: 7.608 ops/ms
Iteration   2: 7.360 ops/ms
Iteration   3: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.691 ±(99.9%) 6.903 ops/ms [Average]
  (min, avg, max) = (7.360, 7.691, 8.103), stdev = 0.378
  CI (99.9%): [0.787, 14.594] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.088 ops/ms
# Warmup Iteration   2: 5.819 ops/ms
# Warmup Iteration   3: 6.835 ops/ms
Iteration   1: 6.873 ops/ms
Iteration   2: 7.314 ops/ms
Iteration   3: 7.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.062 ±(99.9%) 4.147 ops/ms [Average]
  (min, avg, max) = (6.873, 7.062, 7.314), stdev = 0.227
  CI (99.9%): [2.915, 11.210] (assumes normal distribution)


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
# Warmup Iteration   1: 14.086 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.005 ms/op
Iteration   1: 4.095 ±(99.9%) 0.011 ms/op
Iteration   2: 3.807 ±(99.9%) 0.012 ms/op
Iteration   3: 4.148 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.017 ±(99.9%) 3.345 ms/op [Average]
  (min, avg, max) = (3.807, 4.017, 4.148), stdev = 0.183
  CI (99.9%): [0.671, 7.362] (assumes normal distribution)


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
# Warmup Iteration   1: 12.022 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.008 ms/op
Iteration   1: 3.704 ±(99.9%) 0.005 ms/op
Iteration   2: 4.022 ±(99.9%) 0.006 ms/op
Iteration   3: 4.007 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.911 ±(99.9%) 3.274 ms/op [Average]
  (min, avg, max) = (3.704, 3.911, 4.022), stdev = 0.179
  CI (99.9%): [0.637, 7.185] (assumes normal distribution)


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
# Warmup Iteration   1: 13.486 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.003 ms/op
Iteration   1: 4.009 ±(99.9%) 0.010 ms/op
Iteration   2: 4.120 ±(99.9%) 0.006 ms/op
Iteration   3: 3.785 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.971 ±(99.9%) 3.116 ms/op [Average]
  (min, avg, max) = (3.785, 3.971, 4.120), stdev = 0.171
  CI (99.9%): [0.855, 7.088] (assumes normal distribution)


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
# Warmup Iteration   1: 13.631 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.507 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.008 ms/op
Iteration   1: 4.915 ±(99.9%) 0.009 ms/op
Iteration   2: 4.753 ±(99.9%) 0.013 ms/op
Iteration   3: 4.615 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.761 ±(99.9%) 2.744 ms/op [Average]
  (min, avg, max) = (4.615, 4.761, 4.915), stdev = 0.150
  CI (99.9%): [2.017, 7.505] (assumes normal distribution)


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
# Warmup Iteration   1: 12.664 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.363 ±(99.9%) 0.018 ms/op
Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  11.534 ms/op
                 createUser·p0.9999: 22.411 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.956 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  20.683 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   31.326 ms/op

Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  19.262 ms/op
                 createUser·p0.9999: 25.499 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239241
  mean =      4.012 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227 
    [ 2.500,  5.000) = 227598 
    [ 5.000,  7.500) = 9677 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     18.834 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.934 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 11.853 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.013 ms/op
Iteration   1: 3.726 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.747 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  23.691 ms/op
                 existUser·p0.9999: 27.047 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   2: 4.081 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 30.054 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   3: 3.808 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  12.210 ms/op
                 existUser·p0.9999: 30.931 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248180
  mean =      3.866 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 498 
    [ 2.500,  5.000) = 234853 
    [ 5.000,  7.500) = 10340 
    [ 7.500, 10.000) = 1831 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.758 ms/op
     p(99.9900) =     29.989 ms/op
     p(99.9990) =     32.883 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 13.134 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
Iteration   1: 3.804 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  21.880 ms/op
                 getUser·p0.9999: 26.502 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 3.966 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.741 ms/op
                 getUser·p0.999:  11.950 ms/op
                 getUser·p0.9999: 26.376 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  25.607 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245265
  mean =      3.912 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 235720 
    [ 5.000,  7.500) = 7245 
    [ 7.500, 10.000) = 1533 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     28.589 ms/op
     p(99.9990) =     29.706 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.180 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.955 ±(99.9%) 0.020 ms/op
Iteration   1: 4.959 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  26.230 ms/op
                 listUser·p0.9999: 29.855 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 4.681 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   8.608 ms/op
                 listUser·p0.999:  18.792 ms/op
                 listUser·p0.9999: 25.157 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 4.770 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.242 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 21.581 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199778
  mean =      4.801 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 159371 
    [ 5.000,  7.500) = 34108 
    [ 7.500, 10.000) = 4764 
    [10.000, 12.500) = 906 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     21.641 ms/op
     p(99.9900) =     28.247 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.444 ± 11.435  ops/ms
ClientPb.existUser                       thrpt       3   8.084 ±  2.202  ops/ms
ClientPb.getUser                         thrpt       3   7.691 ±  6.903  ops/ms
ClientPb.listUser                        thrpt       3   7.062 ±  4.147  ops/ms
ClientPb.createUser                       avgt       3   4.017 ±  3.345   ms/op
ClientPb.existUser                        avgt       3   3.911 ±  3.274   ms/op
ClientPb.getUser                          avgt       3   3.971 ±  3.116   ms/op
ClientPb.listUser                         avgt       3   4.761 ±  2.744   ms/op
ClientPb.createUser                     sample  239241   4.012 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.894            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.973            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.922            ms/op
ClientPb.createUser:createUser·p0.999   sample          18.834            ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.131            ms/op
ClientPb.createUser:createUser·p1.00    sample          31.326            ms/op
ClientPb.existUser                      sample  248180   3.866 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.475            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.046            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.512            ms/op
ClientPb.existUser:existUser·p0.999     sample          16.758            ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.989            ms/op
ClientPb.existUser:existUser·p1.00      sample          33.194            ms/op
ClientPb.getUser                        sample  245265   3.912 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.376            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.225            ms/op
ClientPb.getUser:getUser·p0.999         sample          21.791            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.589            ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753            ms/op
ClientPb.listUser                       sample  199778   4.801 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.485            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.448            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.480            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.470            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.641            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.247            ms/op
ClientPb.listUser:listUser·p1.00        sample          30.474            ms/op
