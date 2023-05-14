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
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 4.034 ops/ms
# Warmup Iteration   3: 7.663 ops/ms
Iteration   1: 7.607 ops/ms
Iteration   2: 7.991 ops/ms
Iteration   3: 8.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.916 ±(99.9%) 5.096 ops/ms [Average]
  (min, avg, max) = (7.607, 7.916, 8.150), stdev = 0.279
  CI (99.9%): [2.820, 13.012] (assumes normal distribution)


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
# Warmup Iteration   1: 2.347 ops/ms
# Warmup Iteration   2: 6.804 ops/ms
# Warmup Iteration   3: 8.230 ops/ms
Iteration   1: 8.030 ops/ms
Iteration   2: 8.214 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.208 ±(99.9%) 3.192 ops/ms [Average]
  (min, avg, max) = (8.030, 8.208, 8.380), stdev = 0.175
  CI (99.9%): [5.016, 11.400] (assumes normal distribution)


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
# Warmup Iteration   1: 2.244 ops/ms
# Warmup Iteration   2: 6.691 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 7.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.000 ±(99.9%) 2.921 ops/ms [Average]
  (min, avg, max) = (7.902, 8.000, 8.185), stdev = 0.160
  CI (99.9%): [5.079, 10.921] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 5.660 ops/ms
# Warmup Iteration   3: 6.864 ops/ms
Iteration   1: 6.793 ops/ms
Iteration   2: 7.146 ops/ms
Iteration   3: 6.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.901 ±(99.9%) 3.868 ops/ms [Average]
  (min, avg, max) = (6.766, 6.901, 7.146), stdev = 0.212
  CI (99.9%): [3.033, 10.770] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.943 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.009 ms/op
Iteration   1: 4.000 ±(99.9%) 0.010 ms/op
Iteration   2: 3.934 ±(99.9%) 0.014 ms/op
Iteration   3: 3.929 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.954 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.929, 3.954, 4.000), stdev = 0.040
  CI (99.9%): [3.227, 4.682] (assumes normal distribution)


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
# Warmup Iteration   1: 11.538 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.006 ms/op
Iteration   1: 3.729 ±(99.9%) 0.005 ms/op
Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
Iteration   3: 3.812 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.802 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.729, 3.802, 3.866), stdev = 0.069
  CI (99.9%): [2.542, 5.062] (assumes normal distribution)


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
# Warmup Iteration   1: 12.459 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.005 ms/op
Iteration   1: 4.098 ±(99.9%) 0.006 ms/op
Iteration   2: 3.900 ±(99.9%) 0.006 ms/op
Iteration   3: 4.049 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.016 ±(99.9%) 1.881 ms/op [Average]
  (min, avg, max) = (3.900, 4.016, 4.098), stdev = 0.103
  CI (99.9%): [2.134, 5.897] (assumes normal distribution)


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
# Warmup Iteration   1: 12.398 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.131 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.646 ±(99.9%) 0.013 ms/op
Iteration   1: 4.830 ±(99.9%) 0.006 ms/op
Iteration   2: 4.573 ±(99.9%) 0.016 ms/op
Iteration   3: 4.703 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.702 ±(99.9%) 2.342 ms/op [Average]
  (min, avg, max) = (4.573, 4.702, 4.830), stdev = 0.128
  CI (99.9%): [2.360, 7.044] (assumes normal distribution)


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
# Warmup Iteration   1: 13.943 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.753 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.017 ms/op
Iteration   1: 4.060 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  17.145 ms/op
                 createUser·p0.9999: 24.191 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 4.132 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.884 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  24.564 ms/op
                 createUser·p0.9999: 27.304 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  24.330 ms/op
                 createUser·p0.9999: 27.556 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236667
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 413 
    [ 2.500,  5.000) = 223206 
    [ 5.000,  7.500) = 10711 
    [ 7.500, 10.000) = 1666 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 121 

  Percentiles, ms/op:
      p(0.0000) =      1.870 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     22.664 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     29.383 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 10.957 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.013 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  13.242 ms/op
                 existUser·p0.9999: 23.552 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.799 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  22.217 ms/op
                 existUser·p0.9999: 25.775 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 26.320 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252113
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 244 
    [ 2.500,  5.000) = 242178 
    [ 5.000,  7.500) = 8491 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 148 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.479 ms/op
     p(99.9000) =     12.794 ms/op
     p(99.9900) =     25.356 ms/op
     p(99.9990) =     27.635 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 12.645 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.016 ms/op
Iteration   1: 4.104 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.929 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  24.185 ms/op
                 getUser·p0.9999: 31.373 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  20.348 ms/op
                 getUser·p0.9999: 30.700 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 3.968 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  27.497 ms/op
                 getUser·p0.9999: 33.509 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239510
  mean =      4.005 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 226726 
    [ 5.000,  7.500) = 11061 
    [ 7.500, 10.000) = 1041 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     32.802 ms/op
     p(99.9990) =     34.789 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 13.726 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.768 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.786 ±(99.9%) 0.016 ms/op
Iteration   1: 4.765 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  25.068 ms/op
                 listUser·p0.9999: 31.307 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 4.831 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.654 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  16.886 ms/op
                 listUser·p0.9999: 21.676 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.706 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.601 ms/op
                 listUser·p0.9999: 20.356 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201337
  mean =      4.767 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 166370 
    [ 5.000,  7.500) = 28961 
    [ 7.500, 10.000) = 5048 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.358 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     29.849 ms/op
     p(99.9990) =     32.109 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.916 ± 5.096  ops/ms
ClientPb.existUser                       thrpt       3   8.208 ± 3.192  ops/ms
ClientPb.getUser                         thrpt       3   8.000 ± 2.921  ops/ms
ClientPb.listUser                        thrpt       3   6.901 ± 3.868  ops/ms
ClientPb.createUser                       avgt       3   3.954 ± 0.728   ms/op
ClientPb.existUser                        avgt       3   3.802 ± 1.260   ms/op
ClientPb.getUser                          avgt       3   4.016 ± 1.881   ms/op
ClientPb.listUser                         avgt       3   4.702 ± 2.342   ms/op
ClientPb.createUser                     sample  236667   4.053 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.870           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.487           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.664           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.935           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.819           ms/op
ClientPb.existUser                      sample  252113   3.804 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.479           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.794           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.356           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  239510   4.005 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.117           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.802           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  201337   4.767 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.364           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.152           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.849           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
