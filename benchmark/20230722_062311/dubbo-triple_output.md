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
# Warmup Iteration   1: 1.940 ops/ms
# Warmup Iteration   2: 5.166 ops/ms
# Warmup Iteration   3: 8.058 ops/ms
Iteration   1: 9.053 ops/ms
Iteration   2: 9.275 ops/ms
Iteration   3: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.071 ±(99.9%) 3.554 ops/ms [Average]
  (min, avg, max) = (8.886, 9.071, 9.275), stdev = 0.195
  CI (99.9%): [5.517, 12.625] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.456 ops/ms
# Warmup Iteration   2: 7.818 ops/ms
# Warmup Iteration   3: 9.119 ops/ms
Iteration   1: 9.631 ops/ms
Iteration   2: 9.112 ops/ms
Iteration   3: 9.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.350 ±(99.9%) 4.785 ops/ms [Average]
  (min, avg, max) = (9.112, 9.350, 9.631), stdev = 0.262
  CI (99.9%): [4.564, 14.135] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.414 ops/ms
# Warmup Iteration   2: 7.759 ops/ms
# Warmup Iteration   3: 9.082 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.319 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.333 ±(99.9%) 2.005 ops/ms [Average]
  (min, avg, max) = (9.231, 9.333, 9.449), stdev = 0.110
  CI (99.9%): [7.328, 11.338] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 6.122 ops/ms
# Warmup Iteration   3: 7.640 ops/ms
Iteration   1: 7.687 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 8.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.900 ±(99.9%) 3.366 ops/ms [Average]
  (min, avg, max) = (7.687, 7.900, 8.008), stdev = 0.185
  CI (99.9%): [4.534, 11.266] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.241 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.011 ms/op
Iteration   1: 3.438 ±(99.9%) 0.005 ms/op
Iteration   2: 3.430 ±(99.9%) 0.007 ms/op
Iteration   3: 3.390 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.390, 3.419, 3.438), stdev = 0.025
  CI (99.9%): [2.955, 3.883] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.874 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.007 ms/op
Iteration   1: 3.322 ±(99.9%) 0.010 ms/op
Iteration   2: 3.378 ±(99.9%) 0.004 ms/op
Iteration   3: 3.399 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.366 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.322, 3.366, 3.399), stdev = 0.040
  CI (99.9%): [2.645, 4.088] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.986 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.006 ms/op
Iteration   1: 3.527 ±(99.9%) 0.006 ms/op
Iteration   2: 3.548 ±(99.9%) 0.009 ms/op
Iteration   3: 3.432 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.432, 3.502, 3.548), stdev = 0.062
  CI (99.9%): [2.370, 4.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.298 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.009 ms/op
Iteration   1: 4.259 ±(99.9%) 0.006 ms/op
Iteration   2: 4.173 ±(99.9%) 0.011 ms/op
Iteration   3: 4.071 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.168 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (4.071, 4.168, 4.259), stdev = 0.094
  CI (99.9%): [2.446, 5.889] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.504 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.016 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.247 ms/op
                 createUser·p0.999:  19.606 ms/op
                 createUser·p0.9999: 25.681 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  23.662 ms/op
                 createUser·p0.9999: 27.500 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.543 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  20.644 ms/op
                 createUser·p0.9999: 25.756 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277122
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7416 
    [ 2.500,  5.000) = 263859 
    [ 5.000,  7.500) = 4587 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 108 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     26.669 ms/op
     p(99.9990) =     29.506 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.804 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.012 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.843 ms/op
                 existUser·p0.999:  20.806 ms/op
                 existUser·p0.9999: 23.185 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.403 ms/op
                 existUser·p0.999:  10.976 ms/op
                 existUser·p0.9999: 25.436 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.397 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  26.289 ms/op
                 existUser·p0.9999: 29.838 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280147
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11420 
    [ 2.500,  5.000) = 261580 
    [ 5.000,  7.500) = 6168 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     11.319 ms/op
     p(99.9900) =     29.096 ms/op
     p(99.9990) =     30.055 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.885 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.012 ms/op
Iteration   1: 3.585 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  21.618 ms/op
                 getUser·p0.9999: 26.977 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 3.474 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  22.271 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  22.426 ms/op
                 getUser·p0.9999: 29.003 ms/op
                 getUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272981
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3776 
    [ 2.500,  5.000) = 258985 
    [ 5.000,  7.500) = 9128 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 166 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     22.021 ms/op
     p(99.9900) =     27.220 ms/op
     p(99.9990) =     30.426 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.577 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.851 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.014 ms/op
Iteration   1: 4.001 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  24.845 ms/op
                 listUser·p0.9999: 30.343 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   2: 4.137 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  14.562 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.110 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 16.748 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235163
  mean =      4.082 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 226586 
    [ 5.000,  7.500) = 6593 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.204 ms/op
     p(99.9000) =     16.217 ms/op
     p(99.9900) =     28.983 ms/op
     p(99.9990) =     30.833 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.071 ± 3.554  ops/ms
ClientPb.existUser                       thrpt       3   9.350 ± 4.785  ops/ms
ClientPb.getUser                         thrpt       3   9.333 ± 2.005  ops/ms
ClientPb.listUser                        thrpt       3   7.900 ± 3.366  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 0.464   ms/op
ClientPb.existUser                        avgt       3   3.366 ± 0.721   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 1.132   ms/op
ClientPb.listUser                         avgt       3   4.168 ± 1.721   ms/op
ClientPb.createUser                     sample  277122   3.466 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.923           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  280147   3.427 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.586           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.319           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.096           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.409           ms/op
ClientPb.getUser                        sample  272981   3.517 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.220           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  235163   4.082 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.583           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.204           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.217           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.983           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.261           ms/op
