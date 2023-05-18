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
# Warmup Iteration   1: 1.626 ops/ms
# Warmup Iteration   2: 3.752 ops/ms
# Warmup Iteration   3: 6.926 ops/ms
Iteration   1: 7.493 ops/ms
Iteration   2: 7.819 ops/ms
Iteration   3: 7.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.754 ±(99.9%) 4.292 ops/ms [Average]
  (min, avg, max) = (7.493, 7.754, 7.950), stdev = 0.235
  CI (99.9%): [3.462, 12.045] (assumes normal distribution)


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
# Warmup Iteration   1: 2.529 ops/ms
# Warmup Iteration   2: 7.101 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.569 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.340 ±(99.9%) 3.641 ops/ms [Average]
  (min, avg, max) = (8.207, 8.340, 8.569), stdev = 0.200
  CI (99.9%): [4.699, 11.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.167 ops/ms
# Warmup Iteration   2: 6.925 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 8.171 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.312 ±(99.9%) 2.598 ops/ms [Average]
  (min, avg, max) = (8.171, 8.312, 8.456), stdev = 0.142
  CI (99.9%): [5.714, 10.910] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.280 ops/ms
# Warmup Iteration   2: 6.193 ops/ms
# Warmup Iteration   3: 6.791 ops/ms
Iteration   1: 7.268 ops/ms
Iteration   2: 6.953 ops/ms
Iteration   3: 6.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.054 ±(99.9%) 3.377 ops/ms [Average]
  (min, avg, max) = (6.942, 7.054, 7.268), stdev = 0.185
  CI (99.9%): [3.677, 10.431] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 12.760 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.004 ms/op
Iteration   1: 3.836 ±(99.9%) 0.009 ms/op
Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
Iteration   3: 3.791 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.793 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.750, 3.793, 3.836), stdev = 0.043
  CI (99.9%): [3.010, 4.575] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.418 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.003 ms/op
Iteration   1: 3.851 ±(99.9%) 0.006 ms/op
Iteration   2: 3.852 ±(99.9%) 0.007 ms/op
Iteration   3: 3.722 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.808 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.722, 3.808, 3.852), stdev = 0.075
  CI (99.9%): [2.441, 5.175] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.538 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.010 ms/op
Iteration   1: 4.149 ±(99.9%) 0.007 ms/op
Iteration   2: 3.787 ±(99.9%) 0.010 ms/op
Iteration   3: 3.900 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.946 ±(99.9%) 3.380 ms/op [Average]
  (min, avg, max) = (3.787, 3.946, 4.149), stdev = 0.185
  CI (99.9%): [0.566, 7.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.461 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.678 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.742 ±(99.9%) 0.008 ms/op
Iteration   1: 4.671 ±(99.9%) 0.006 ms/op
Iteration   2: 4.265 ±(99.9%) 0.015 ms/op
Iteration   3: 4.418 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.451 ±(99.9%) 3.746 ms/op [Average]
  (min, avg, max) = (4.265, 4.451, 4.671), stdev = 0.205
  CI (99.9%): [0.705, 8.198] (assumes normal distribution)


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
# Warmup Iteration   1: 11.713 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.018 ms/op
Iteration   1: 3.958 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  11.359 ms/op
                 createUser·p0.9999: 25.551 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.670 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  24.543 ms/op
                 createUser·p0.9999: 29.327 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   3: 3.719 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  25.659 ms/op
                 createUser·p0.9999: 33.096 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 254011
  mean =      3.778 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 807 
    [ 2.500,  5.000) = 241950 
    [ 5.000,  7.500) = 9803 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     30.494 ms/op
     p(99.9990) =     33.484 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.369 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.012 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 25.409 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.812 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  23.593 ms/op
                 existUser·p0.9999: 26.471 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.695 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.269 ms/op
                 existUser·p0.999:  11.518 ms/op
                 existUser·p0.9999: 30.574 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255145
  mean =      3.761 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 448 
    [ 2.500,  5.000) = 246837 
    [ 5.000,  7.500) = 6761 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     11.532 ms/op
     p(99.9900) =     29.966 ms/op
     p(99.9990) =     30.762 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 11.190 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  15.349 ms/op
                 getUser·p0.9999: 27.954 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   2: 3.830 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  22.905 ms/op
                 getUser·p0.9999: 25.292 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.810 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  24.707 ms/op
                 getUser·p0.9999: 28.888 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247058
  mean =      3.884 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 273 
    [ 2.500,  5.000) = 235163 
    [ 5.000,  7.500) = 9155 
    [ 7.500, 10.000) = 1510 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     22.739 ms/op
     p(99.9900) =     28.354 ms/op
     p(99.9990) =     29.888 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 13.713 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.374 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.018 ms/op
Iteration   1: 4.509 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  25.985 ms/op
                 listUser·p0.9999: 32.012 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   2: 4.601 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.668 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  17.811 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 4.571 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 21.694 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 210288
  mean =      4.560 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 185827 
    [ 5.000,  7.500) = 19402 
    [ 7.500, 10.000) = 4063 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     19.529 ms/op
     p(99.9900) =     31.125 ms/op
     p(99.9990) =     33.023 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.754 ± 4.292  ops/ms
ClientPb.existUser                       thrpt       3   8.340 ± 3.641  ops/ms
ClientPb.getUser                         thrpt       3   8.312 ± 2.598  ops/ms
ClientPb.listUser                        thrpt       3   7.054 ± 3.377  ops/ms
ClientPb.createUser                       avgt       3   3.793 ± 0.782   ms/op
ClientPb.existUser                        avgt       3   3.808 ± 1.367   ms/op
ClientPb.getUser                          avgt       3   3.946 ± 3.380   ms/op
ClientPb.listUser                         avgt       3   4.451 ± 3.746   ms/op
ClientPb.createUser                     sample  254011   3.778 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.024           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.494           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  255145   3.761 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.532           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.966           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  247058   3.884 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.718           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.739           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.354           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  210288   4.560 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.374           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.529           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.063           ms/op
