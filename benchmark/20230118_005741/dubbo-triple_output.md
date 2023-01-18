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
# Warmup Iteration   1: 1.639 ops/ms
# Warmup Iteration   2: 3.500 ops/ms
# Warmup Iteration   3: 6.985 ops/ms
Iteration   1: 7.329 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.788 ±(99.9%) 7.285 ops/ms [Average]
  (min, avg, max) = (7.329, 7.788, 8.057), stdev = 0.399
  CI (99.9%): [0.503, 15.073] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.317 ops/ms
# Warmup Iteration   2: 7.169 ops/ms
# Warmup Iteration   3: 8.329 ops/ms
Iteration   1: 8.470 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 8.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.393 ±(99.9%) 5.922 ops/ms [Average]
  (min, avg, max) = (8.037, 8.393, 8.673), stdev = 0.325
  CI (99.9%): [2.471, 14.315] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.096 ops/ms
# Warmup Iteration   2: 5.666 ops/ms
# Warmup Iteration   3: 7.602 ops/ms
Iteration   1: 7.721 ops/ms
Iteration   2: 8.125 ops/ms
Iteration   3: 8.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.053 ±(99.9%) 5.534 ops/ms [Average]
  (min, avg, max) = (7.721, 8.053, 8.315), stdev = 0.303
  CI (99.9%): [2.519, 13.588] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.976 ops/ms
# Warmup Iteration   2: 5.311 ops/ms
# Warmup Iteration   3: 6.851 ops/ms
Iteration   1: 6.739 ops/ms
Iteration   2: 6.831 ops/ms
Iteration   3: 7.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.911 ±(99.9%) 4.069 ops/ms [Average]
  (min, avg, max) = (6.739, 6.911, 7.163), stdev = 0.223
  CI (99.9%): [2.841, 10.980] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.263 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.007 ms/op
Iteration   1: 4.263 ±(99.9%) 0.006 ms/op
Iteration   2: 4.364 ±(99.9%) 0.006 ms/op
Iteration   3: 4.334 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.320 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (4.263, 4.320, 4.364), stdev = 0.052
  CI (99.9%): [3.370, 5.271] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.290 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.003 ms/op
Iteration   1: 3.763 ±(99.9%) 0.005 ms/op
Iteration   2: 4.018 ±(99.9%) 0.009 ms/op
Iteration   3: 3.872 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.884 ±(99.9%) 2.335 ms/op [Average]
  (min, avg, max) = (3.763, 3.884, 4.018), stdev = 0.128
  CI (99.9%): [1.549, 6.219] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.532 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.008 ms/op
Iteration   1: 3.850 ±(99.9%) 0.009 ms/op
Iteration   2: 3.843 ±(99.9%) 0.010 ms/op
Iteration   3: 3.909 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.867 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.843, 3.867, 3.909), stdev = 0.036
  CI (99.9%): [3.207, 4.527] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.876 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.798 ±(99.9%) 0.008 ms/op
Iteration   1: 4.741 ±(99.9%) 0.010 ms/op
Iteration   2: 4.632 ±(99.9%) 0.007 ms/op
Iteration   3: 4.642 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.672 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (4.632, 4.672, 4.741), stdev = 0.060
  CI (99.9%): [3.575, 5.768] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.553 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 4.982 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.023 ms/op
Iteration   1: 4.133 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  16.286 ms/op
                 createUser·p0.9999: 25.797 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 3.887 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  25.780 ms/op
                 createUser·p0.9999: 29.207 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 3.942 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  28.175 ms/op
                 createUser·p0.9999: 32.423 ms/op
                 createUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240695
  mean =      3.985 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189 
    [ 2.500,  5.000) = 227488 
    [ 5.000,  7.500) = 10444 
    [ 7.500, 10.000) = 1564 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 125 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     25.199 ms/op
     p(99.9900) =     31.193 ms/op
     p(99.9990) =     32.853 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.918 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.226 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  9.876 ms/op
                 existUser·p0.9999: 28.563 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 3.725 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.975 ms/op
                 existUser·p0.999:  23.961 ms/op
                 existUser·p0.9999: 45.208 ms/op
                 existUser·p1.00:   47.907 ms/op

Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  12.409 ms/op
                 existUser·p0.9999: 28.824 ms/op
                 existUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252661
  mean =      3.799 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 245291 
    [ 5.000, 10.000) = 6971 
    [10.000, 15.000) = 162 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 143 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     13.053 ms/op
     p(99.9900) =     43.581 ms/op
     p(99.9990) =     47.251 ms/op
     p(99.9999) =     47.907 ms/op
    p(100.0000) =     47.907 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.245 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.015 ms/op
Iteration   1: 4.078 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 24.357 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  14.949 ms/op
                 getUser·p0.9999: 25.311 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.888 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  24.864 ms/op
                 getUser·p0.9999: 27.248 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239201
  mean =      4.010 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 224955 
    [ 5.000,  7.500) = 12122 
    [ 7.500, 10.000) = 1427 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 93 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     21.030 ms/op
     p(99.9900) =     26.482 ms/op
     p(99.9990) =     28.876 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.851 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.287 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.196 ±(99.9%) 0.020 ms/op
Iteration   1: 4.823 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  28.365 ms/op
                 listUser·p0.9999: 33.161 ms/op
                 listUser·p1.00:   33.489 ms/op

Iteration   2: 4.785 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   9.481 ms/op
                 listUser·p0.999:  17.700 ms/op
                 listUser·p0.9999: 20.992 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 4.858 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198974
  mean =      4.822 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 158931 
    [ 5.000,  7.500) = 33271 
    [ 7.500, 10.000) = 5537 
    [10.000, 12.500) = 657 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     19.563 ms/op
     p(99.9900) =     31.281 ms/op
     p(99.9990) =     33.262 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.788 ± 7.285  ops/ms
ClientPb.existUser                       thrpt       3   8.393 ± 5.922  ops/ms
ClientPb.getUser                         thrpt       3   8.053 ± 5.534  ops/ms
ClientPb.listUser                        thrpt       3   6.911 ± 4.069  ops/ms
ClientPb.createUser                       avgt       3   4.320 ± 0.951   ms/op
ClientPb.existUser                        avgt       3   3.884 ± 2.335   ms/op
ClientPb.getUser                          avgt       3   3.867 ± 0.660   ms/op
ClientPb.listUser                         avgt       3   4.672 ± 1.096   ms/op
ClientPb.createUser                     sample  240695   3.985 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.386           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.684           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.199           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.325           ms/op
ClientPb.existUser                      sample  252661   3.799 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.393           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.653           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.581           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.907           ms/op
ClientPb.getUser                        sample  239201   4.010 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.745           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.030           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.482           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  198974   4.822 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.737           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.563           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.281           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.489           ms/op
