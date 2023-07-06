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
# Warmup Iteration   1: 1.802 ops/ms
# Warmup Iteration   2: 4.302 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.944 ±(99.9%) 5.462 ops/ms [Average]
  (min, avg, max) = (7.598, 7.944, 8.118), stdev = 0.299
  CI (99.9%): [2.482, 13.406] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.322 ops/ms
# Warmup Iteration   2: 7.168 ops/ms
# Warmup Iteration   3: 8.575 ops/ms
Iteration   1: 8.544 ops/ms
Iteration   2: 8.631 ops/ms
Iteration   3: 8.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.715 ±(99.9%) 4.112 ops/ms [Average]
  (min, avg, max) = (8.544, 8.715, 8.970), stdev = 0.225
  CI (99.9%): [4.603, 12.827] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.390 ops/ms
# Warmup Iteration   2: 6.871 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 8.209 ops/ms
Iteration   2: 8.117 ops/ms
Iteration   3: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.207 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (8.117, 8.207, 8.294), stdev = 0.088
  CI (99.9%): [6.592, 9.821] (assumes normal distribution)


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
# Warmup Iteration   1: 1.946 ops/ms
# Warmup Iteration   2: 5.819 ops/ms
# Warmup Iteration   3: 6.936 ops/ms
Iteration   1: 6.707 ops/ms
Iteration   2: 7.214 ops/ms
Iteration   3: 6.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.964 ±(99.9%) 4.625 ops/ms [Average]
  (min, avg, max) = (6.707, 6.964, 7.214), stdev = 0.253
  CI (99.9%): [2.339, 11.588] (assumes normal distribution)


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
# Warmup Iteration   1: 13.386 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.009 ms/op
Iteration   1: 3.996 ±(99.9%) 0.005 ms/op
Iteration   2: 4.020 ±(99.9%) 0.006 ms/op
Iteration   3: 3.914 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.977 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.914, 3.977, 4.020), stdev = 0.055
  CI (99.9%): [2.968, 4.986] (assumes normal distribution)


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
# Warmup Iteration   1: 10.617 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.011 ms/op
Iteration   1: 3.641 ±(99.9%) 0.009 ms/op
Iteration   2: 3.663 ±(99.9%) 0.011 ms/op
Iteration   3: 3.773 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.692 ±(99.9%) 1.288 ms/op [Average]
  (min, avg, max) = (3.641, 3.692, 3.773), stdev = 0.071
  CI (99.9%): [2.404, 4.980] (assumes normal distribution)


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
# Warmup Iteration   1: 12.159 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.010 ms/op
Iteration   1: 3.864 ±(99.9%) 0.013 ms/op
Iteration   2: 3.990 ±(99.9%) 0.007 ms/op
Iteration   3: 3.829 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.894 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (3.829, 3.894, 3.990), stdev = 0.085
  CI (99.9%): [2.349, 5.439] (assumes normal distribution)


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
# Warmup Iteration   1: 13.991 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.828 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.011 ms/op
Iteration   1: 4.641 ±(99.9%) 0.008 ms/op
Iteration   2: 4.444 ±(99.9%) 0.021 ms/op
Iteration   3: 4.525 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.537 ±(99.9%) 1.811 ms/op [Average]
  (min, avg, max) = (4.444, 4.537, 4.641), stdev = 0.099
  CI (99.9%): [2.726, 6.347] (assumes normal distribution)


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
# Warmup Iteration   1: 11.974 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.017 ms/op
Iteration   1: 4.013 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.815 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.349 ms/op
                 createUser·p0.999:  20.481 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 4.074 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  24.655 ms/op
                 createUser·p0.9999: 27.291 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 4.072 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 35.278 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236887
  mean =      4.053 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 755 
    [ 2.500,  5.000) = 219173 
    [ 5.000,  7.500) = 15093 
    [ 7.500, 10.000) = 1199 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     21.332 ms/op
     p(99.9900) =     34.623 ms/op
     p(99.9990) =     36.238 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 10.830 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
Iteration   1: 3.765 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  21.168 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   2: 3.739 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   7.313 ms/op
                 existUser·p0.999:  14.721 ms/op
                 existUser·p0.9999: 27.030 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.776 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.869 ms/op
                 existUser·p0.999:  11.075 ms/op
                 existUser·p0.9999: 31.067 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255095
  mean =      3.760 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1308 
    [ 2.500,  5.000) = 244531 
    [ 5.000,  7.500) = 7619 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.318 ms/op
     p(99.9900) =     30.096 ms/op
     p(99.9990) =     32.458 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 11.942 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.014 ms/op
Iteration   1: 3.763 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  14.355 ms/op
                 getUser·p0.9999: 27.935 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 3.881 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  23.841 ms/op
                 getUser·p0.9999: 26.797 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.922 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  11.575 ms/op
                 getUser·p0.9999: 30.230 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 248817
  mean =      3.854 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 403 
    [ 2.500,  5.000) = 238055 
    [ 5.000,  7.500) = 8253 
    [ 7.500, 10.000) = 1499 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     14.031 ms/op
     p(99.9900) =     29.285 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 11.616 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.156 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.015 ms/op
Iteration   1: 4.755 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  23.672 ms/op
                 listUser·p0.9999: 26.872 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 4.649 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  19.254 ms/op
                 listUser·p0.9999: 25.898 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   3: 4.551 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.016 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 18.348 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206349
  mean =      4.650 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 175500 
    [ 5.000,  7.500) = 26481 
    [ 7.500, 10.000) = 3395 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     25.792 ms/op
     p(99.9990) =     28.502 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.944 ± 5.462  ops/ms
ClientPb.existUser                       thrpt       3   8.715 ± 4.112  ops/ms
ClientPb.getUser                         thrpt       3   8.207 ± 1.614  ops/ms
ClientPb.listUser                        thrpt       3   6.964 ± 4.625  ops/ms
ClientPb.createUser                       avgt       3   3.977 ± 1.009   ms/op
ClientPb.existUser                        avgt       3   3.692 ± 1.288   ms/op
ClientPb.getUser                          avgt       3   3.894 ± 1.545   ms/op
ClientPb.listUser                         avgt       3   4.537 ± 1.811   ms/op
ClientPb.createUser                     sample  236887   4.053 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.470           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.332           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.623           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  255095   3.760 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.432           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.873           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.318           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.096           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  248817   3.854 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.266           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.285           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  206349   4.650 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.809           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.792           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.639           ms/op
