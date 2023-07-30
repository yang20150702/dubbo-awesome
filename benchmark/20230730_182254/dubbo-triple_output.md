# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.671 ops/ms
# Warmup Iteration   2: 3.306 ops/ms
# Warmup Iteration   3: 6.992 ops/ms
Iteration   1: 7.439 ops/ms
Iteration   2: 8.111 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.889 ±(99.9%) 7.120 ops/ms [Average]
  (min, avg, max) = (7.439, 7.889, 8.119), stdev = 0.390
  CI (99.9%): [0.769, 15.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 6.683 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.298 ±(99.9%) 8.214 ops/ms [Average]
  (min, avg, max) = (7.781, 8.298, 8.603), stdev = 0.450
  CI (99.9%): [0.084, 16.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.366 ops/ms
# Warmup Iteration   2: 6.623 ops/ms
# Warmup Iteration   3: 7.774 ops/ms
Iteration   1: 7.803 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.068 ±(99.9%) 4.179 ops/ms [Average]
  (min, avg, max) = (7.803, 8.068, 8.208), stdev = 0.229
  CI (99.9%): [3.888, 12.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
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
# Warmup Iteration   2: 5.067 ops/ms
# Warmup Iteration   3: 6.581 ops/ms
Iteration   1: 6.662 ops/ms
Iteration   2: 6.798 ops/ms
Iteration   3: 6.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.683 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (6.589, 6.683, 6.798), stdev = 0.106
  CI (99.9%): [4.750, 8.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.726 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.896 ±(99.9%) 0.009 ms/op
Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
Iteration   3: 3.966 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.924 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.896, 3.924, 3.966), stdev = 0.037
  CI (99.9%): [3.248, 4.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.300 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.929 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.757 ±(99.9%) 0.005 ms/op
Iteration   2: 3.871 ±(99.9%) 0.004 ms/op
Iteration   3: 3.758 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.795 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (3.757, 3.795, 3.871), stdev = 0.066
  CI (99.9%): [2.597, 4.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.170 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.212 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.004 ms/op
Iteration   1: 4.060 ±(99.9%) 0.010 ms/op
Iteration   2: 4.000 ±(99.9%) 0.006 ms/op
Iteration   3: 3.781 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.947 ±(99.9%) 2.675 ms/op [Average]
  (min, avg, max) = (3.781, 3.947, 4.060), stdev = 0.147
  CI (99.9%): [1.271, 6.622] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.897 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.875 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.967 ±(99.9%) 0.011 ms/op
Iteration   1: 4.872 ±(99.9%) 0.009 ms/op
Iteration   2: 4.639 ±(99.9%) 0.013 ms/op
Iteration   3: 4.637 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.716 ±(99.9%) 2.462 ms/op [Average]
  (min, avg, max) = (4.637, 4.716, 4.872), stdev = 0.135
  CI (99.9%): [2.254, 7.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.156 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.395 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.450 ±(99.9%) 0.019 ms/op
Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.798 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  24.315 ms/op
                 createUser·p0.9999: 26.154 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 4.126 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  12.795 ms/op
                 createUser·p0.9999: 31.433 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 4.162 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  29.134 ms/op
                 createUser·p0.9999: 34.029 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232921
  mean =      4.121 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185 
    [ 2.500,  5.000) = 215246 
    [ 5.000,  7.500) = 14802 
    [ 7.500, 10.000) = 1887 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     24.838 ms/op
     p(99.9900) =     32.365 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.180 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.916 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.014 ms/op
Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.960 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.229 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 28.541 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 24.407 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   3: 3.876 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  23.440 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249123
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 280 
    [ 2.500,  5.000) = 240911 
    [ 5.000,  7.500) = 6209 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.990 ms/op
     p(99.9900) =     27.888 ms/op
     p(99.9990) =     29.132 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.254 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.011 ms/op
Iteration   1: 4.192 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   9.175 ms/op
                 getUser·p0.999:  22.727 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   7.523 ms/op
                 getUser·p0.999:  18.865 ms/op
                 getUser·p0.9999: 26.667 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  26.258 ms/op
                 getUser·p0.9999: 29.696 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235745
  mean =      4.070 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 222051 
    [ 5.000,  7.500) = 9584 
    [ 7.500, 10.000) = 2888 
    [10.000, 12.500) = 687 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     30.130 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.421 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.796 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.018 ms/op
Iteration   1: 4.768 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.788 ms/op
                 listUser·p0.999:  24.964 ms/op
                 listUser·p0.9999: 26.776 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 4.675 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  17.350 ms/op
                 listUser·p0.9999: 20.893 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   3: 4.694 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  16.679 ms/op
                 listUser·p0.9999: 18.488 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203725
  mean =      4.712 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 176621 
    [ 5.000,  7.500) = 22803 
    [ 7.500, 10.000) = 3239 
    [10.000, 12.500) = 513 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     26.202 ms/op
     p(99.9990) =     26.998 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.889 ± 7.120  ops/ms
ClientPb.existUser                       thrpt       3   8.298 ± 8.214  ops/ms
ClientPb.getUser                         thrpt       3   8.068 ± 4.179  ops/ms
ClientPb.listUser                        thrpt       3   6.683 ± 1.933  ops/ms
ClientPb.createUser                       avgt       3   3.924 ± 0.676   ms/op
ClientPb.existUser                        avgt       3   3.795 ± 1.198   ms/op
ClientPb.getUser                          avgt       3   3.947 ± 2.675   ms/op
ClientPb.listUser                         avgt       3   4.716 ± 2.462   ms/op
ClientPb.createUser                     sample  232921   4.121 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.475           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.838           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  249123   3.852 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.366           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.990           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.888           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  235745   4.070 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.647           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.774           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.443           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  203725   4.712 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.202           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.514           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.202           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
