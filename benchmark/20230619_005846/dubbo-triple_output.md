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
# Warmup Iteration   1: 1.733 ops/ms
# Warmup Iteration   2: 3.643 ops/ms
# Warmup Iteration   3: 7.618 ops/ms
Iteration   1: 7.763 ops/ms
Iteration   2: 8.324 ops/ms
Iteration   3: 7.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.996 ±(99.9%) 5.343 ops/ms [Average]
  (min, avg, max) = (7.763, 7.996, 8.324), stdev = 0.293
  CI (99.9%): [2.653, 13.339] (assumes normal distribution)


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
# Warmup Iteration   1: 2.254 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 8.169 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.315 ±(99.9%) 3.882 ops/ms [Average]
  (min, avg, max) = (8.169, 8.315, 8.559), stdev = 0.213
  CI (99.9%): [4.433, 12.197] (assumes normal distribution)


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
# Warmup Iteration   1: 2.496 ops/ms
# Warmup Iteration   2: 7.024 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 8.034 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.859 ±(99.9%) 3.783 ops/ms [Average]
  (min, avg, max) = (7.630, 7.859, 8.034), stdev = 0.207
  CI (99.9%): [4.076, 11.642] (assumes normal distribution)


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
# Warmup Iteration   1: 1.970 ops/ms
# Warmup Iteration   2: 5.782 ops/ms
# Warmup Iteration   3: 6.747 ops/ms
Iteration   1: 6.987 ops/ms
Iteration   2: 6.891 ops/ms
Iteration   3: 7.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.962 ±(99.9%) 1.133 ops/ms [Average]
  (min, avg, max) = (6.891, 6.962, 7.007), stdev = 0.062
  CI (99.9%): [5.829, 8.095] (assumes normal distribution)


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
# Warmup Iteration   1: 12.121 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.009 ms/op
Iteration   1: 3.904 ±(99.9%) 0.008 ms/op
Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
Iteration   3: 3.880 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.888 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.879, 3.888, 3.904), stdev = 0.014
  CI (99.9%): [3.626, 4.150] (assumes normal distribution)


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
# Warmup Iteration   1: 13.194 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.010 ms/op
Iteration   1: 3.667 ±(99.9%) 0.011 ms/op
Iteration   2: 3.863 ±(99.9%) 0.006 ms/op
Iteration   3: 3.850 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.793 ±(99.9%) 2.001 ms/op [Average]
  (min, avg, max) = (3.667, 3.793, 3.863), stdev = 0.110
  CI (99.9%): [1.792, 5.794] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 12.205 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.397 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.004 ms/op
Iteration   1: 3.993 ±(99.9%) 0.010 ms/op
Iteration   2: 3.921 ±(99.9%) 0.007 ms/op
Iteration   3: 3.940 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.952 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.921, 3.952, 3.993), stdev = 0.037
  CI (99.9%): [3.272, 4.631] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.211 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.012 ms/op
Iteration   1: 4.423 ±(99.9%) 0.013 ms/op
Iteration   2: 4.443 ±(99.9%) 0.013 ms/op
Iteration   3: 4.516 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.461 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (4.423, 4.461, 4.516), stdev = 0.049
  CI (99.9%): [3.569, 5.352] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.284 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.172 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.020 ms/op
Iteration   1: 4.203 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.169 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  14.465 ms/op
                 createUser·p0.9999: 26.260 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.958 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  25.965 ms/op
                 createUser·p0.9999: 32.995 ms/op
                 createUser·p1.00:   34.275 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.931 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  10.860 ms/op
                 createUser·p0.9999: 31.529 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237446
  mean =      4.041 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 293 
    [ 2.500,  5.000) = 217437 
    [ 5.000,  7.500) = 17347 
    [ 7.500, 10.000) = 1850 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     33.432 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.692 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.013 ms/op
Iteration   1: 3.721 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.814 ms/op
                 existUser·p0.999:  22.383 ms/op
                 existUser·p0.9999: 24.904 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.745 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.952 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  11.177 ms/op
                 existUser·p0.9999: 25.688 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.843 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  26.356 ms/op
                 existUser·p0.9999: 30.223 ms/op
                 existUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254592
  mean =      3.769 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 356 
    [ 2.500,  5.000) = 245870 
    [ 5.000,  7.500) = 7073 
    [ 7.500, 10.000) = 887 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     21.968 ms/op
     p(99.9900) =     28.627 ms/op
     p(99.9990) =     30.718 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.517 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.016 ms/op
Iteration   1: 3.934 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  23.468 ms/op
                 getUser·p0.9999: 28.077 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   2: 3.881 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  25.315 ms/op
                 getUser·p0.9999: 30.196 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   3: 4.099 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  15.675 ms/op
                 getUser·p0.9999: 29.596 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241908
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 232356 
    [ 5.000,  7.500) = 7593 
    [ 7.500, 10.000) = 1257 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.748 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     23.408 ms/op
     p(99.9900) =     29.616 ms/op
     p(99.9990) =     30.744 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 14.443 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.744 ±(99.9%) 0.017 ms/op
Iteration   1: 4.565 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  24.321 ms/op
                 listUser·p0.9999: 26.444 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   2: 4.546 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  17.030 ms/op
                 listUser·p0.9999: 20.641 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.437 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.904 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 17.426 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212214
  mean =      4.515 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 197012 
    [ 5.000,  7.500) = 11673 
    [ 7.500, 10.000) = 2456 
    [10.000, 12.500) = 552 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     25.912 ms/op
     p(99.9990) =     26.813 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.996 ± 5.343  ops/ms
ClientPb.existUser                       thrpt       3   8.315 ± 3.882  ops/ms
ClientPb.getUser                         thrpt       3   7.859 ± 3.783  ops/ms
ClientPb.listUser                        thrpt       3   6.962 ± 1.133  ops/ms
ClientPb.createUser                       avgt       3   3.888 ± 0.262   ms/op
ClientPb.existUser                        avgt       3   3.793 ± 2.001   ms/op
ClientPb.getUser                          avgt       3   3.952 ± 0.679   ms/op
ClientPb.listUser                         avgt       3   4.461 ± 0.892   ms/op
ClientPb.createUser                     sample  237446   4.041 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.515           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.276           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  254592   3.769 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.524           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.968           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.627           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.769           ms/op
ClientPb.getUser                        sample  241908   3.969 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.748           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.408           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.616           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  212214   4.515 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.925           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
