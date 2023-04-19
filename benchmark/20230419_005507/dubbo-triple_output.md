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
# Warmup Iteration   1: 1.367 ops/ms
# Warmup Iteration   2: 3.206 ops/ms
# Warmup Iteration   3: 5.954 ops/ms
Iteration   1: 5.606 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 6.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.988 ±(99.9%) 6.946 ops/ms [Average]
  (min, avg, max) = (5.606, 5.988, 6.368), stdev = 0.381
  CI (99.9%): [≈ 0, 12.934] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 5.738 ops/ms
# Warmup Iteration   3: 6.423 ops/ms
Iteration   1: 6.427 ops/ms
Iteration   2: 6.582 ops/ms
Iteration   3: 6.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.552 ±(99.9%) 2.062 ops/ms [Average]
  (min, avg, max) = (6.427, 6.552, 6.646), stdev = 0.113
  CI (99.9%): [4.489, 8.614] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.957 ops/ms
# Warmup Iteration   2: 5.586 ops/ms
# Warmup Iteration   3: 6.020 ops/ms
Iteration   1: 5.939 ops/ms
Iteration   2: 5.954 ops/ms
Iteration   3: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.112 ±(99.9%) 5.246 ops/ms [Average]
  (min, avg, max) = (5.939, 6.112, 6.444), stdev = 0.288
  CI (99.9%): [0.866, 11.358] (assumes normal distribution)


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
# Warmup Iteration   1: 1.907 ops/ms
# Warmup Iteration   2: 4.661 ops/ms
# Warmup Iteration   3: 4.955 ops/ms
Iteration   1: 5.539 ops/ms
Iteration   2: 5.482 ops/ms
Iteration   3: 5.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.490 ±(99.9%) 0.830 ops/ms [Average]
  (min, avg, max) = (5.449, 5.490, 5.539), stdev = 0.045
  CI (99.9%): [4.660, 6.319] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.950 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.166 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.011 ms/op
Iteration   1: 5.326 ±(99.9%) 0.015 ms/op
Iteration   2: 5.007 ±(99.9%) 0.012 ms/op
Iteration   3: 4.935 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.089 ±(99.9%) 3.794 ms/op [Average]
  (min, avg, max) = (4.935, 5.089, 5.326), stdev = 0.208
  CI (99.9%): [1.295, 8.883] (assumes normal distribution)


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
# Warmup Iteration   1: 15.761 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.932 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.006 ms/op
Iteration   1: 4.708 ±(99.9%) 0.011 ms/op
Iteration   2: 4.724 ±(99.9%) 0.009 ms/op
Iteration   3: 4.653 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.695 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (4.653, 4.695, 4.724), stdev = 0.037
  CI (99.9%): [4.012, 5.378] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 17.875 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.871 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.241 ±(99.9%) 0.011 ms/op
Iteration   1: 5.128 ±(99.9%) 0.014 ms/op
Iteration   2: 4.891 ±(99.9%) 0.015 ms/op
Iteration   3: 5.125 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.048 ±(99.9%) 2.482 ms/op [Average]
  (min, avg, max) = (4.891, 5.048, 5.128), stdev = 0.136
  CI (99.9%): [2.566, 7.530] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.708 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.791 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.944 ±(99.9%) 0.015 ms/op
Iteration   1: 5.842 ±(99.9%) 0.017 ms/op
Iteration   2: 6.182 ±(99.9%) 0.019 ms/op
Iteration   3: 6.314 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.113 ±(99.9%) 4.450 ms/op [Average]
  (min, avg, max) = (5.842, 6.113, 6.314), stdev = 0.244
  CI (99.9%): [1.663, 10.562] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.689 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.120 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.165 ±(99.9%) 0.030 ms/op
Iteration   1: 5.199 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   7.078 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  24.543 ms/op
                 createUser·p0.9999: 27.968 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   2: 5.349 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.168 ms/op
                 createUser·p0.99:   9.863 ms/op
                 createUser·p0.999:  27.893 ms/op
                 createUser·p0.9999: 31.754 ms/op
                 createUser·p1.00:   32.309 ms/op

Iteration   3: 5.194 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.351 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  28.434 ms/op
                 createUser·p0.9999: 42.926 ms/op
                 createUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182930
  mean =      5.247 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 90203 
    [ 5.000, 10.000) = 91016 
    [10.000, 15.000) = 1410 
    [15.000, 20.000) = 109 
    [20.000, 25.000) = 16 
    [25.000, 30.000) = 105 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      9.793 ms/op
     p(99.9000) =     24.648 ms/op
     p(99.9900) =     40.771 ms/op
     p(99.9990) =     43.278 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.886 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.373 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.063 ±(99.9%) 0.016 ms/op
Iteration   1: 5.058 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.662 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  22.446 ms/op
                 existUser·p0.9999: 35.434 ms/op
                 existUser·p1.00:   35.783 ms/op

Iteration   2: 5.159 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.250 ms/op
                 existUser·p0.95:   6.955 ms/op
                 existUser·p0.99:   9.191 ms/op
                 existUser·p0.999:  26.018 ms/op
                 existUser·p0.9999: 33.056 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   3: 4.942 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.081 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   5.898 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  16.340 ms/op
                 existUser·p0.9999: 30.769 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189873
  mean =      5.052 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 113146 
    [ 5.000,  7.500) = 70519 
    [ 7.500, 10.000) = 4839 
    [10.000, 12.500) = 748 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     21.439 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     35.665 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 14.884 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.661 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.092 ±(99.9%) 0.019 ms/op
Iteration   1: 5.205 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   7.274 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  22.035 ms/op
                 getUser·p0.9999: 25.622 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 5.185 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.707 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   8.050 ms/op
                 getUser·p0.99:   11.108 ms/op
                 getUser·p0.999:  21.735 ms/op
                 getUser·p0.9999: 27.421 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 5.029 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.163 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   5.988 ms/op
                 getUser·p0.95:   6.775 ms/op
                 getUser·p0.99:   9.994 ms/op
                 getUser·p0.999:  24.321 ms/op
                 getUser·p0.9999: 29.742 ms/op
                 getUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186823
  mean =      5.138 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 109940 
    [ 5.000, 10.000) = 73964 
    [10.000, 15.000) = 2395 
    [15.000, 20.000) = 318 
    [20.000, 25.000) = 114 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     28.177 ms/op
     p(99.9990) =     31.821 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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
# Warmup Iteration   1: 18.921 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.626 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.418 ±(99.9%) 0.026 ms/op
Iteration   1: 6.239 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.328 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  24.110 ms/op
                 listUser·p0.9999: 27.255 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 5.855 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.619 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  24.602 ms/op
                 listUser·p0.9999: 27.316 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 6.003 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   11.174 ms/op
                 listUser·p0.999:  18.997 ms/op
                 listUser·p0.9999: 21.434 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159081
  mean =      6.028 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 17967 
    [ 5.000,  7.500) = 129267 
    [ 7.500, 10.000) = 8742 
    [10.000, 12.500) = 2014 
    [12.500, 15.000) = 550 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      2.712 ms/op
     p(50.0000) =      5.743 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.431 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.988 ± 6.946  ops/ms
ClientPb.existUser                       thrpt       3   6.552 ± 2.062  ops/ms
ClientPb.getUser                         thrpt       3   6.112 ± 5.246  ops/ms
ClientPb.listUser                        thrpt       3   5.490 ± 0.830  ops/ms
ClientPb.createUser                       avgt       3   5.089 ± 3.794   ms/op
ClientPb.existUser                        avgt       3   4.695 ± 0.683   ms/op
ClientPb.getUser                          avgt       3   5.048 ± 2.482   ms/op
ClientPb.listUser                         avgt       3   6.113 ± 4.450   ms/op
ClientPb.createUser                     sample  182930   5.247 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.793           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.648           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.771           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.713           ms/op
ClientPb.existUser                      sample  189873   5.052 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.745           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.372           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.439           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.865           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  186823   5.138 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.163           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.955           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.177           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.698           ms/op
ClientPb.listUser                       sample  159081   6.028 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.176           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.223           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.774           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.066           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.508           ms/op
