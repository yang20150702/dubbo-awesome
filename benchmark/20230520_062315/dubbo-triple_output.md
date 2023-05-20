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
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 3.341 ops/ms
# Warmup Iteration   3: 7.360 ops/ms
Iteration   1: 7.551 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.881 ±(99.9%) 5.967 ops/ms [Average]
  (min, avg, max) = (7.551, 7.881, 8.205), stdev = 0.327
  CI (99.9%): [1.914, 13.848] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.297 ops/ms
# Warmup Iteration   2: 6.864 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.661 ops/ms
Iteration   2: 8.386 ops/ms
Iteration   3: 8.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.484 ±(99.9%) 2.801 ops/ms [Average]
  (min, avg, max) = (8.386, 8.484, 8.661), stdev = 0.154
  CI (99.9%): [5.683, 11.285] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 6.950 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.220 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.189 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (8.110, 8.189, 8.239), stdev = 0.069
  CI (99.9%): [6.924, 9.455] (assumes normal distribution)


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
# Warmup Iteration   1: 2.050 ops/ms
# Warmup Iteration   2: 6.120 ops/ms
# Warmup Iteration   3: 6.641 ops/ms
Iteration   1: 6.896 ops/ms
Iteration   2: 7.010 ops/ms
Iteration   3: 7.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.970 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (6.896, 6.970, 7.010), stdev = 0.064
  CI (99.9%): [5.798, 8.141] (assumes normal distribution)


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
# Warmup Iteration   1: 14.717 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.317 ±(99.9%) 0.004 ms/op
Iteration   1: 4.031 ±(99.9%) 0.006 ms/op
Iteration   2: 4.061 ±(99.9%) 0.010 ms/op
Iteration   3: 3.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.995 ±(99.9%) 1.627 ms/op [Average]
  (min, avg, max) = (3.894, 3.995, 4.061), stdev = 0.089
  CI (99.9%): [2.369, 5.622] (assumes normal distribution)


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
# Warmup Iteration   1: 10.621 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.006 ms/op
Iteration   1: 3.846 ±(99.9%) 0.011 ms/op
Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
Iteration   3: 3.735 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.768 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (3.722, 3.768, 3.846), stdev = 0.068
  CI (99.9%): [2.521, 5.014] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.835 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.829 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.008 ms/op
Iteration   1: 4.300 ±(99.9%) 0.008 ms/op
Iteration   2: 3.852 ±(99.9%) 0.008 ms/op
Iteration   3: 3.955 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.035 ±(99.9%) 4.281 ms/op [Average]
  (min, avg, max) = (3.852, 4.035, 4.300), stdev = 0.235
  CI (99.9%): [≈ 0, 8.316] (assumes normal distribution)


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
# Warmup Iteration   1: 13.837 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.919 ±(99.9%) 0.004 ms/op
Iteration   1: 4.566 ±(99.9%) 0.013 ms/op
Iteration   2: 4.487 ±(99.9%) 0.015 ms/op
Iteration   3: 4.709 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.587 ±(99.9%) 2.053 ms/op [Average]
  (min, avg, max) = (4.487, 4.587, 4.709), stdev = 0.113
  CI (99.9%): [2.534, 6.640] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.030 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.017 ms/op
Iteration   1: 4.057 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.848 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 26.349 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.936 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  18.295 ms/op
                 createUser·p0.9999: 30.961 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   3: 4.032 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.923 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  28.312 ms/op
                 createUser·p0.9999: 32.381 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239582
  mean =      4.007 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 354 
    [ 2.500,  5.000) = 225446 
    [ 5.000,  7.500) = 11696 
    [ 7.500, 10.000) = 1375 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     23.831 ms/op
     p(99.9900) =     31.625 ms/op
     p(99.9990) =     32.821 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.319 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.011 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.862 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   7.198 ms/op
                 existUser·p0.999:  12.269 ms/op
                 existUser·p0.9999: 24.573 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.867 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.971 ms/op
                 existUser·p0.999:  11.879 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.742 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  24.920 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250959
  mean =      3.824 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 195 
    [ 2.500,  5.000) = 240315 
    [ 5.000,  7.500) = 7838 
    [ 7.500, 10.000) = 2026 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 110 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     19.375 ms/op
     p(99.9900) =     27.325 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.975 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.015 ms/op
Iteration   1: 4.033 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  24.258 ms/op
                 getUser·p0.9999: 26.675 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  9.404 ms/op
                 getUser·p0.9999: 28.337 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 3.923 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.019 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  27.295 ms/op
                 getUser·p0.9999: 48.693 ms/op
                 getUser·p1.00:   49.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241199
  mean =      3.979 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 228082 
    [ 5.000, 10.000) = 12359 
    [10.000, 15.000) = 432 
    [15.000, 20.000) = 63 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 151 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     24.209 ms/op
     p(99.9900) =     46.884 ms/op
     p(99.9990) =     49.229 ms/op
     p(99.9999) =     49.349 ms/op
    p(100.0000) =     49.349 ms/op


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
# Warmup Iteration   1: 15.444 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.384 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.016 ms/op
Iteration   1: 4.716 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  25.008 ms/op
                 listUser·p0.9999: 27.139 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   2: 4.789 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.049 ms/op
                 listUser·p0.9999: 27.259 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 4.744 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  18.468 ms/op
                 listUser·p0.9999: 20.825 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202059
  mean =      4.750 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 162041 
    [ 5.000,  7.500) = 35146 
    [ 7.500, 10.000) = 3722 
    [10.000, 12.500) = 593 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     20.609 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     28.114 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.881 ± 5.967  ops/ms
ClientPb.existUser                       thrpt       3   8.484 ± 2.801  ops/ms
ClientPb.getUser                         thrpt       3   8.189 ± 1.265  ops/ms
ClientPb.listUser                        thrpt       3   6.970 ± 1.172  ops/ms
ClientPb.createUser                       avgt       3   3.995 ± 1.627   ms/op
ClientPb.existUser                        avgt       3   3.768 ± 1.247   ms/op
ClientPb.getUser                          avgt       3   4.035 ± 4.281   ms/op
ClientPb.listUser                         avgt       3   4.587 ± 2.053   ms/op
ClientPb.createUser                     sample  239582   4.007 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.591           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.625           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  250959   3.824 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.544           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.594           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.375           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.325           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  241199   3.979 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.589           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.209           ms/op
ClientPb.getUser:getUser·p0.9999        sample          46.884           ms/op
ClientPb.getUser:getUser·p1.00          sample          49.349           ms/op
ClientPb.listUser                       sample  202059   4.750 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.609           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.246           ms/op
