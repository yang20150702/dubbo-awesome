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
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 3.807 ops/ms
# Warmup Iteration   3: 7.395 ops/ms
Iteration   1: 7.423 ops/ms
Iteration   2: 7.853 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.804 ±(99.9%) 6.542 ops/ms [Average]
  (min, avg, max) = (7.423, 7.804, 8.135), stdev = 0.359
  CI (99.9%): [1.262, 14.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.397 ops/ms
# Warmup Iteration   2: 5.444 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.342 ops/ms
Iteration   2: 8.357 ops/ms
Iteration   3: 8.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.464 ±(99.9%) 3.621 ops/ms [Average]
  (min, avg, max) = (8.342, 8.464, 8.693), stdev = 0.198
  CI (99.9%): [4.843, 12.086] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 6.429 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 7.921 ops/ms
Iteration   2: 8.168 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.149 ±(99.9%) 4.000 ops/ms [Average]
  (min, avg, max) = (7.921, 8.149, 8.358), stdev = 0.219
  CI (99.9%): [4.149, 12.149] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.996 ops/ms
# Warmup Iteration   2: 5.063 ops/ms
# Warmup Iteration   3: 6.667 ops/ms
Iteration   1: 7.027 ops/ms
Iteration   2: 6.852 ops/ms
Iteration   3: 6.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.927 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (6.852, 6.927, 7.027), stdev = 0.090
  CI (99.9%): [5.282, 8.572] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.020 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.327 ±(99.9%) 0.009 ms/op
Iteration   1: 4.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.893 ±(99.9%) 0.008 ms/op
Iteration   3: 4.074 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.998 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.893, 3.998, 4.074), stdev = 0.094
  CI (99.9%): [2.279, 5.717] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.728 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.006 ms/op
Iteration   1: 4.063 ±(99.9%) 0.004 ms/op
Iteration   2: 3.739 ±(99.9%) 0.009 ms/op
Iteration   3: 3.834 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.879 ±(99.9%) 3.043 ms/op [Average]
  (min, avg, max) = (3.739, 3.879, 4.063), stdev = 0.167
  CI (99.9%): [0.836, 6.921] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.520 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.721 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.983 ±(99.9%) 0.008 ms/op
Iteration   2: 3.922 ±(99.9%) 0.010 ms/op
Iteration   3: 3.991 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.965 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.922, 3.965, 3.991), stdev = 0.038
  CI (99.9%): [3.274, 4.657] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.819 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.492 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.010 ms/op
Iteration   1: 4.676 ±(99.9%) 0.009 ms/op
Iteration   2: 4.658 ±(99.9%) 0.010 ms/op
Iteration   3: 4.698 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.677 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (4.658, 4.677, 4.698), stdev = 0.020
  CI (99.9%): [4.310, 5.045] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.527 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.920 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.322 ±(99.9%) 0.018 ms/op
Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  23.645 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 4.016 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.688 ms/op
                 createUser·p0.999:  25.681 ms/op
                 createUser·p0.9999: 32.309 ms/op
                 createUser·p1.00:   33.096 ms/op

Iteration   3: 4.056 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  19.961 ms/op
                 createUser·p0.9999: 31.418 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238812
  mean =      4.020 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 559 
    [ 2.500,  5.000) = 223259 
    [ 5.000,  7.500) = 12573 
    [ 7.500, 10.000) = 1684 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.536 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     31.363 ms/op
     p(99.9990) =     32.823 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.065 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.013 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  15.806 ms/op
                 existUser·p0.9999: 25.879 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   2: 3.898 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 27.197 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.833 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 30.373 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248617
  mean =      3.862 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 317 
    [ 2.500,  5.000) = 233214 
    [ 5.000,  7.500) = 13211 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     29.238 ms/op
     p(99.9990) =     31.378 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 13.753 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.017 ms/op
Iteration   1: 4.038 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  23.485 ms/op
                 getUser·p0.9999: 29.366 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   2: 4.121 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.042 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  16.093 ms/op
                 getUser·p0.9999: 27.967 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 4.008 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.038 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  26.221 ms/op
                 getUser·p0.9999: 33.818 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236530
  mean =      4.055 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 116 
    [ 2.500,  5.000) = 226027 
    [ 5.000,  7.500) = 8113 
    [ 7.500, 10.000) = 1483 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     23.589 ms/op
     p(99.9900) =     32.291 ms/op
     p(99.9990) =     35.497 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 15.023 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.771 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.016 ms/op
Iteration   1: 4.803 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.324 ms/op
                 listUser·p0.99:   9.261 ms/op
                 listUser·p0.999:  24.805 ms/op
                 listUser·p0.9999: 28.957 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   2: 4.743 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 30.417 ms/op
                 listUser·p1.00:   31.982 ms/op

Iteration   3: 4.588 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  17.889 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203590
  mean =      4.710 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 173434 
    [ 5.000,  7.500) = 25117 
    [ 7.500, 10.000) = 3756 
    [10.000, 12.500) = 645 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     29.095 ms/op
     p(99.9990) =     31.847 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.804 ± 6.542  ops/ms
ClientPb.existUser                       thrpt       3   8.464 ± 3.621  ops/ms
ClientPb.getUser                         thrpt       3   8.149 ± 4.000  ops/ms
ClientPb.listUser                        thrpt       3   6.927 ± 1.645  ops/ms
ClientPb.createUser                       avgt       3   3.998 ± 1.719   ms/op
ClientPb.existUser                        avgt       3   3.879 ± 3.043   ms/op
ClientPb.getUser                          avgt       3   3.965 ± 0.691   ms/op
ClientPb.listUser                         avgt       3   4.677 ± 0.368   ms/op
ClientPb.createUser                     sample  238812   4.020 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.858           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.536           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.691           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.363           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.096           ms/op
ClientPb.existUser                      sample  248617   3.862 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.550           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  236530   4.055 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.341           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.589           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.291           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.586           ms/op
ClientPb.listUser                       sample  203590   4.710 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.168           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.095           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.982           ms/op
