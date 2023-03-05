# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 4.438 ops/ms
# Warmup Iteration   3: 7.462 ops/ms
Iteration   1: 7.925 ops/ms
Iteration   2: 8.659 ops/ms
Iteration   3: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.274 ±(99.9%) 6.726 ops/ms [Average]
  (min, avg, max) = (7.925, 8.274, 8.659), stdev = 0.369
  CI (99.9%): [1.548, 14.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.807 ops/ms
# Warmup Iteration   2: 7.038 ops/ms
# Warmup Iteration   3: 8.401 ops/ms
Iteration   1: 8.662 ops/ms
Iteration   2: 8.607 ops/ms
Iteration   3: 8.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.623 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (8.601, 8.623, 8.662), stdev = 0.034
  CI (99.9%): [8.006, 9.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 6.956 ops/ms
# Warmup Iteration   3: 8.028 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 8.742 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.512 ±(99.9%) 4.692 ops/ms [Average]
  (min, avg, max) = (8.234, 8.512, 8.742), stdev = 0.257
  CI (99.9%): [3.820, 13.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 5.814 ops/ms
# Warmup Iteration   3: 6.787 ops/ms
Iteration   1: 7.039 ops/ms
Iteration   2: 7.022 ops/ms
Iteration   3: 7.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.126 ±(99.9%) 3.025 ops/ms [Average]
  (min, avg, max) = (7.022, 7.126, 7.317), stdev = 0.166
  CI (99.9%): [4.101, 10.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.025 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.005 ms/op
Iteration   1: 3.755 ±(99.9%) 0.007 ms/op
Iteration   2: 3.776 ±(99.9%) 0.011 ms/op
Iteration   3: 3.765 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.765 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.755, 3.765, 3.776), stdev = 0.011
  CI (99.9%): [3.566, 3.964] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.726 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.007 ms/op
Iteration   1: 3.760 ±(99.9%) 0.008 ms/op
Iteration   2: 3.688 ±(99.9%) 0.006 ms/op
Iteration   3: 3.655 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.701 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.655, 3.701, 3.760), stdev = 0.053
  CI (99.9%): [2.725, 4.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.486 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.959 ±(99.9%) 0.005 ms/op
Iteration   2: 3.769 ±(99.9%) 0.013 ms/op
Iteration   3: 3.832 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.853 ±(99.9%) 1.764 ms/op [Average]
  (min, avg, max) = (3.769, 3.853, 3.959), stdev = 0.097
  CI (99.9%): [2.089, 5.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.656 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.127 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.519 ±(99.9%) 0.013 ms/op
Iteration   1: 4.481 ±(99.9%) 0.012 ms/op
Iteration   2: 4.362 ±(99.9%) 0.016 ms/op
Iteration   3: 4.522 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.455 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (4.362, 4.455, 4.522), stdev = 0.083
  CI (99.9%): [2.934, 5.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.823 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.016 ms/op
Iteration   1: 3.914 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  24.495 ms/op
                 createUser·p0.9999: 32.372 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   2: 3.898 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  25.887 ms/op
                 createUser·p0.9999: 28.685 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 3.818 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  24.747 ms/op
                 createUser·p0.9999: 30.245 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247489
  mean =      3.876 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 625 
    [ 2.500,  5.000) = 237056 
    [ 5.000,  7.500) = 8448 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     24.789 ms/op
     p(99.9900) =     30.908 ms/op
     p(99.9990) =     33.244 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.836 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
Iteration   1: 3.596 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   6.082 ms/op
                 existUser·p0.999:  22.775 ms/op
                 existUser·p0.9999: 25.533 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 3.761 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.952 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.738 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  24.764 ms/op
                 existUser·p0.9999: 34.800 ms/op
                 existUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 259637
  mean =      3.697 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 809 
    [ 2.500,  5.000) = 251039 
    [ 5.000,  7.500) = 6469 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     33.423 ms/op
     p(99.9990) =     35.968 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.028 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  12.993 ms/op
                 getUser·p0.9999: 24.661 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.791 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.032 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  24.073 ms/op
                 getUser·p0.9999: 26.790 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.892 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.962 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.926 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  17.277 ms/op
                 getUser·p0.9999: 37.342 ms/op
                 getUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244402
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227 
    [ 2.500,  5.000) = 231253 
    [ 5.000,  7.500) = 10696 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     16.724 ms/op
     p(99.9900) =     35.819 ms/op
     p(99.9990) =     38.644 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.758 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.911 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.767 ±(99.9%) 0.018 ms/op
Iteration   1: 4.605 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  24.332 ms/op
                 listUser·p0.9999: 29.537 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 4.485 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.344 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.526 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.729 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 21.518 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208294
  mean =      4.604 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 183513 
    [ 5.000,  7.500) = 20982 
    [ 7.500, 10.000) = 2670 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     28.132 ms/op
     p(99.9990) =     30.013 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.274 ± 6.726  ops/ms
ClientPb.existUser                       thrpt       3   8.623 ± 0.617  ops/ms
ClientPb.getUser                         thrpt       3   8.512 ± 4.692  ops/ms
ClientPb.listUser                        thrpt       3   7.126 ± 3.025  ops/ms
ClientPb.createUser                       avgt       3   3.765 ± 0.199   ms/op
ClientPb.existUser                        avgt       3   3.701 ± 0.976   ms/op
ClientPb.getUser                          avgt       3   3.853 ± 1.764   ms/op
ClientPb.listUser                         avgt       3   4.455 ± 1.521   ms/op
ClientPb.createUser                     sample  247489   3.876 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.903           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.789           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.908           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.260           ms/op
ClientPb.existUser                      sample  259637   3.697 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.268           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.423           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.356           ms/op
ClientPb.getUser                        sample  244402   3.924 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.581           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.819           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.863           ms/op
ClientPb.listUser                       sample  208294   4.604 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.436           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.268           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
