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
# Warmup Iteration   1: 1.627 ops/ms
# Warmup Iteration   2: 3.861 ops/ms
# Warmup Iteration   3: 7.177 ops/ms
Iteration   1: 7.615 ops/ms
Iteration   2: 7.520 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.721 ±(99.9%) 4.945 ops/ms [Average]
  (min, avg, max) = (7.520, 7.721, 8.029), stdev = 0.271
  CI (99.9%): [2.777, 12.666] (assumes normal distribution)


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
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 6.568 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 8.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.371 ±(99.9%) 4.303 ops/ms [Average]
  (min, avg, max) = (8.229, 8.371, 8.643), stdev = 0.236
  CI (99.9%): [4.067, 12.674] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.961 ops/ms
# Warmup Iteration   2: 6.444 ops/ms
# Warmup Iteration   3: 7.631 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 8.005 ops/ms
Iteration   3: 7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.900 ±(99.9%) 1.684 ops/ms [Average]
  (min, avg, max) = (7.834, 7.900, 8.005), stdev = 0.092
  CI (99.9%): [6.216, 9.584] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
# Warmup Iteration   2: 5.483 ops/ms
# Warmup Iteration   3: 6.731 ops/ms
Iteration   1: 6.350 ops/ms
Iteration   2: 6.587 ops/ms
Iteration   3: 6.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.627 ±(99.9%) 5.452 ops/ms [Average]
  (min, avg, max) = (6.350, 6.627, 6.943), stdev = 0.299
  CI (99.9%): [1.174, 12.079] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.441 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.624 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.007 ms/op
Iteration   1: 4.075 ±(99.9%) 0.009 ms/op
Iteration   2: 4.027 ±(99.9%) 0.009 ms/op
Iteration   3: 4.190 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.097 ±(99.9%) 1.526 ms/op [Average]
  (min, avg, max) = (4.027, 4.097, 4.190), stdev = 0.084
  CI (99.9%): [2.571, 5.624] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.003 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.005 ms/op
Iteration   1: 3.960 ±(99.9%) 0.005 ms/op
Iteration   2: 3.964 ±(99.9%) 0.007 ms/op
Iteration   3: 4.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.980 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.960, 3.980, 4.017), stdev = 0.032
  CI (99.9%): [3.400, 4.561] (assumes normal distribution)


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
# Warmup Iteration   1: 12.698 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.006 ms/op
Iteration   1: 4.086 ±(99.9%) 0.005 ms/op
Iteration   2: 4.155 ±(99.9%) 0.007 ms/op
Iteration   3: 3.931 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.057 ±(99.9%) 2.095 ms/op [Average]
  (min, avg, max) = (3.931, 4.057, 4.155), stdev = 0.115
  CI (99.9%): [1.962, 6.152] (assumes normal distribution)


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
# Warmup Iteration   1: 14.958 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.088 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.986 ±(99.9%) 0.007 ms/op
Iteration   1: 4.925 ±(99.9%) 0.007 ms/op
Iteration   2: 4.779 ±(99.9%) 0.015 ms/op
Iteration   3: 4.662 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.789 ±(99.9%) 2.404 ms/op [Average]
  (min, avg, max) = (4.662, 4.789, 4.925), stdev = 0.132
  CI (99.9%): [2.384, 7.193] (assumes normal distribution)


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
# Warmup Iteration   1: 14.403 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.010 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.017 ms/op
Iteration   1: 4.070 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.778 ms/op
                 createUser·p0.99:   7.899 ms/op
                 createUser·p0.999:  24.983 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   30.245 ms/op

Iteration   3: 4.011 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.853 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.404 ms/op
                 createUser·p0.999:  28.699 ms/op
                 createUser·p0.9999: 32.970 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238619
  mean =      4.020 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 224281 
    [ 5.000,  7.500) = 11783 
    [ 7.500, 10.000) = 1789 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     24.982 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     33.675 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 12.484 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  24.155 ms/op
                 existUser·p0.9999: 25.687 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.843 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.733 ms/op
                 existUser·p0.9999: 27.237 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 3.932 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  26.313 ms/op
                 existUser·p0.9999: 29.127 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246058
  mean =      3.900 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170 
    [ 2.500,  5.000) = 234988 
    [ 5.000,  7.500) = 8768 
    [ 7.500, 10.000) = 1431 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.776 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     23.722 ms/op
     p(99.9900) =     28.324 ms/op
     p(99.9990) =     30.230 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 14.184 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.013 ms/op
Iteration   1: 4.032 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   8.243 ms/op
                 getUser·p0.999:  14.856 ms/op
                 getUser·p0.9999: 26.809 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 3.947 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.066 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  26.340 ms/op
                 getUser·p0.9999: 28.013 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.981 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 30.507 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240640
  mean =      3.986 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 226565 
    [ 5.000,  7.500) = 10924 
    [ 7.500, 10.000) = 2149 
    [10.000, 12.500) = 638 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.776 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     14.791 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     31.076 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 15.316 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.744 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.956 ±(99.9%) 0.018 ms/op
Iteration   1: 4.776 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   9.167 ms/op
                 listUser·p0.999:  26.411 ms/op
                 listUser·p0.9999: 29.584 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 5.038 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  19.399 ms/op
                 listUser·p0.9999: 23.733 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.760 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197590
  mean =      4.854 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 159438 
    [ 5.000,  7.500) = 31416 
    [ 7.500, 10.000) = 4990 
    [10.000, 12.500) = 973 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     21.779 ms/op
     p(99.9900) =     28.909 ms/op
     p(99.9990) =     30.417 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.721 ± 4.945  ops/ms
ClientPb.existUser                       thrpt       3   8.371 ± 4.303  ops/ms
ClientPb.getUser                         thrpt       3   7.900 ± 1.684  ops/ms
ClientPb.listUser                        thrpt       3   6.627 ± 5.452  ops/ms
ClientPb.createUser                       avgt       3   4.097 ± 1.526   ms/op
ClientPb.existUser                        avgt       3   3.980 ± 0.581   ms/op
ClientPb.getUser                          avgt       3   4.057 ± 2.095   ms/op
ClientPb.listUser                         avgt       3   4.789 ± 2.404   ms/op
ClientPb.createUser                     sample  238619   4.020 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.438           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.506           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  246058   3.900 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.776           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.448           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.722           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  240640   3.986 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.776           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.791           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.950           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  197590   4.854 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.909           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.769           ms/op
